.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.bootstrap Environment

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.core.filestore ConfigFileReader

.. java:import:: org.motechproject.config.core.filestore ConfigLocationFileStore

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.core.service.impl.mapper BootstrapConfigPropertyMapper

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.cache.annotation Cacheable

.. java:import:: org.springframework.cache.annotation Caching

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io File

.. java:import:: java.io FileWriter

.. java:import:: java.io IOException

.. java:import:: java.io Writer

.. java:import:: java.nio.file FileSystemException

.. java:import:: java.util Properties

CoreConfigurationServiceImpl
============================

.. java:package:: org.motechproject.config.core.service.impl
   :noindex:

.. java:type:: @Component public class CoreConfigurationServiceImpl implements CoreConfigurationService

   Implementation of \ :java:ref:`org.motechproject.config.core.service.CoreConfigurationService`\ .

   This class is concerned with managing the Bootstrap configuration.

Fields
------
BOOTSTRAP_PROPERTIES
^^^^^^^^^^^^^^^^^^^^

.. java:field:: static final String BOOTSTRAP_PROPERTIES
   :outertype: CoreConfigurationServiceImpl

Constructors
------------
CoreConfigurationServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public CoreConfigurationServiceImpl(ConfigFileReader configFileReader, Environment environment, ConfigLocationFileStore configLocationFileStore)
   :outertype: CoreConfigurationServiceImpl

Methods
-------
addConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void addConfigLocation(String location) throws FileSystemException
   :outertype: CoreConfigurationServiceImpl

evictMotechCoreSettingsCache
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void evictMotechCoreSettingsCache()
   :outertype: CoreConfigurationServiceImpl

getConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ConfigLocation getConfigLocation()
   :outertype: CoreConfigurationServiceImpl

getDefaultBootstrapFile
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  File getDefaultBootstrapFile(FileAccessType accessType)
   :outertype: CoreConfigurationServiceImpl

loadBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override @Caching public BootstrapConfig loadBootstrapConfig()
   :outertype: CoreConfigurationServiceImpl

   This method is used to return the bootstrap configuration

   Try to Load and return the bootstrap configuration in the following order: - Environment Variable: MOTECH_CONFIG_DIR - bootstrap props are in MOTECH_CONFIG_DIR/bootstrap.properties - Environment Variables: MOTECH_DB_URL, MOTECH_DB_USERNAME, MOTECH_DB_PASSWORD - Database config is loaded from these environment variables. MOTECH_TENANT_ID - Tenant ID to be used. If not specified, “DEFAULT” will be used as the tenant id. MOTECH_CONFIG_SOURCE - Configuration source to be used. - Default config location - bootstrap props in bootstrap.properties file from the default location. Default location of bootstrap.properties file is specified in config-locations.properties.

   Returns the Bootstrapconfig if bootstrap config is defined in any of the above locations.

   :return: BootstrapConfig object

saveBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void saveBootstrapConfig(BootstrapConfig bootstrapConfig)
   :outertype: CoreConfigurationServiceImpl

   Saves the bootstrap configuration provided, to the default Bootstrap file location.

   :param bootstrapConfig:

