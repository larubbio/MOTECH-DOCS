.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.collections MapUtils

.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.log4j Logger

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.commons.api MotechMapUtils

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.domain ModulePropertiesRecord

.. java:import:: org.motechproject.config.repository AllModuleProperties

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.config.repository AllSettings

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.cache.annotation Cacheable

.. java:import:: org.springframework.cache.annotation Caching

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.core.io ResourceLoader

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.io BufferedWriter

.. java:import:: java.io File

.. java:import:: java.io FileFilter

.. java:import:: java.io FileInputStream

.. java:import:: java.io FileOutputStream

.. java:import:: java.io FileWriter

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.security DigestInputStream

.. java:import:: java.security MessageDigest

.. java:import:: java.security NoSuchAlgorithmException

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

.. java:import:: java.util.zip ZipEntry

.. java:import:: java.util.zip ZipOutputStream

ConfigurationServiceImpl
========================

.. java:package:: org.motechproject.config.service.impl
   :noindex:

.. java:type:: @Service public class ConfigurationServiceImpl implements ConfigurationService

   Default implementation of \ :java:ref:`org.motechproject.config.service.ConfigurationService`\ .

Constructors
------------
ConfigurationServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ConfigurationServiceImpl(CoreConfigurationService coreConfigurationService, AllSettings allSettings, AllModuleProperties allModuleProperties, ConfigLoader configLoader, ResourceLoader resourceLoader)
   :outertype: ConfigurationServiceImpl

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: @Override public void addOrUpdate(File file)
   :outertype: ConfigurationServiceImpl

addOrUpdateProperties
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void addOrUpdateProperties(String module, String version, String bundle, String filename, Properties newProperties, Properties defaultProperties) throws IOException
   :outertype: ConfigurationServiceImpl

createZipWithConfigFiles
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public FileInputStream createZipWithConfigFiles(String propertyFile, String fileName) throws IOException
   :outertype: ConfigurationServiceImpl

delete
^^^^^^

.. java:method:: @Override public void delete(String module)
   :outertype: ConfigurationServiceImpl

deleteByBundle
^^^^^^^^^^^^^^

.. java:method:: @Override public void deleteByBundle(String module)
   :outertype: ConfigurationServiceImpl

evictMotechSettingsCache
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void evictMotechSettingsCache()
   :outertype: ConfigurationServiceImpl

getAllModuleProperties
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Map<String, Properties> getAllModuleProperties(String module, Map<String, Properties> allDefaultProperties) throws IOException
   :outertype: ConfigurationServiceImpl

getConfigSource
^^^^^^^^^^^^^^^

.. java:method:: @Override public ConfigSource getConfigSource()
   :outertype: ConfigurationServiceImpl

getModuleProperties
^^^^^^^^^^^^^^^^^^^

.. java:method:: public Properties getModuleProperties(String module, String filename, Properties defaultProperties) throws IOException
   :outertype: ConfigurationServiceImpl

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override @Caching public MotechSettings getPlatformSettings()
   :outertype: ConfigurationServiceImpl

getRawConfig
^^^^^^^^^^^^

.. java:method:: @Override public InputStream getRawConfig(String module, String filename, Resource resource) throws IOException
   :outertype: ConfigurationServiceImpl

listRawConfigNames
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<String> listRawConfigNames(String module)
   :outertype: ConfigurationServiceImpl

loadBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public BootstrapConfig loadBootstrapConfig()
   :outertype: ConfigurationServiceImpl

loadConfig
^^^^^^^^^^

.. java:method:: @Override public SettingsRecord loadConfig()
   :outertype: ConfigurationServiceImpl

loadDefaultConfig
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public SettingsRecord loadDefaultConfig()
   :outertype: ConfigurationServiceImpl

processExistingConfigs
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void processExistingConfigs(List<File> files)
   :outertype: ConfigurationServiceImpl

rawConfigExists
^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean rawConfigExists(String module, String filename)
   :outertype: ConfigurationServiceImpl

registersProperties
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean registersProperties(String module, String filename)
   :outertype: ConfigurationServiceImpl

removeProperties
^^^^^^^^^^^^^^^^

.. java:method:: public void removeProperties(String module, String filename)
   :outertype: ConfigurationServiceImpl

requiresConfigurationFiles
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean requiresConfigurationFiles()
   :outertype: ConfigurationServiceImpl

retrieveRegisteredBundleNames
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<String> retrieveRegisteredBundleNames()
   :outertype: ConfigurationServiceImpl

save
^^^^

.. java:method:: @Override public void save(BootstrapConfig bootstrapConfig)
   :outertype: ConfigurationServiceImpl

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void savePlatformSettings(Properties settings)
   :outertype: ConfigurationServiceImpl

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void savePlatformSettings(MotechSettings settings)
   :outertype: ConfigurationServiceImpl

saveRawConfig
^^^^^^^^^^^^^

.. java:method:: @Override public void saveRawConfig(String module, String version, String bundle, String filename, InputStream rawData) throws IOException
   :outertype: ConfigurationServiceImpl

setConfigAnnotation
^^^^^^^^^^^^^^^^^^^

.. java:method:: @javax.annotation.Resource public void setConfigAnnotation(Properties configAnnotation)
   :outertype: ConfigurationServiceImpl

setDefaultConfig
^^^^^^^^^^^^^^^^

.. java:method:: @javax.annotation.Resource public void setDefaultConfig(Properties defaultConfig)
   :outertype: ConfigurationServiceImpl

setPlatformSetting
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setPlatformSetting(String key, String value)
   :outertype: ConfigurationServiceImpl

setResourceLoader
^^^^^^^^^^^^^^^^^

.. java:method::  void setResourceLoader(ResourceLoader resourceLoader)
   :outertype: ConfigurationServiceImpl

updateConfigLocation
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateConfigLocation(String newConfigLocation)
   :outertype: ConfigurationServiceImpl

updatePropertiesAfterReinstallation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updatePropertiesAfterReinstallation(String module, String version, String bundle, String filename, Properties defaultProperties, Properties newProperties) throws IOException
   :outertype: ConfigurationServiceImpl

