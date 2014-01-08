.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.springframework.cache.annotation CacheEvict

.. java:import:: java.nio.file FileSystemException

CoreConfigurationService
========================

.. java:package:: org.motechproject.config.core.service
   :noindex:

.. java:type:: public interface CoreConfigurationService

   Loads and saves the core configuration required to start the Motech instance.

Fields
------
CORE_SETTINGS_CACHE_NAME
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  String CORE_SETTINGS_CACHE_NAME
   :outertype: CoreConfigurationService

Methods
-------
addConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method::  void addConfigLocation(String location) throws FileSystemException
   :outertype: CoreConfigurationService

   Adds the new config location to the list of existing config locations where configurations are loaded from in the file system.

   :param location: config location to add.

evictMotechCoreSettingsCache
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void evictMotechCoreSettingsCache()
   :outertype: CoreConfigurationService

getConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method::  ConfigLocation getConfigLocation()
   :outertype: CoreConfigurationService

   Returns the config location where all the config files are present.

   :return: configLocation.

loadBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method::  BootstrapConfig loadBootstrapConfig()
   :outertype: CoreConfigurationService

   Loads the bootstrap configuration.

   :return: bootstrap configuration.

saveBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void saveBootstrapConfig(BootstrapConfig bootstrapConfig)
   :outertype: CoreConfigurationService

   Saves the bootstrap configuration

   :param bootstrapConfig: Bootstrap config

