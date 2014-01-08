.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.springframework.cache.annotation CacheEvict

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

ConfigurationService
====================

.. java:package:: org.motechproject.config.service
   :noindex:

.. java:type:: public interface ConfigurationService

   Central configuration service that monitors and manages configurations.

Fields
------
SETTINGS_CACHE_NAME
^^^^^^^^^^^^^^^^^^^

.. java:field::  String SETTINGS_CACHE_NAME
   :outertype: ConfigurationService

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method::  void addOrUpdate(File file)
   :outertype: ConfigurationService

   Saves both property and raw configurations in FILE mode only. Files are classified as either raw config or properties based on the extension of the file.

   :param file: File to read configuration from.

addOrUpdateProperties
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void addOrUpdateProperties(String module, String version, String bundle, String filename, Properties newProperties, Properties defaultProperties) throws IOException
   :outertype: ConfigurationService

   Depending on the config source, it will either store properties in the DB or file. Only properties that are different from the default ones are stored. If the properties database record or file doesn't exist yet for the given module, it will be created.

   :param module: The module we wish to update properties for
   :param version: Version of updated bundle
   :param bundle: Symbolic name of updated bundle
   :param filename: Resource filename
   :param newProperties: New properties to store
   :param defaultProperties: Default properties of the module

createZipWithConfigFiles
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  FileInputStream createZipWithConfigFiles(String propertyFile, String fileName) throws IOException
   :outertype: ConfigurationService

   Uses current configuration and default one to find changed properties and then connects them with annotations. Moreover creates file with non default configurations and packs is into the zip file.

   :param propertyFile: name of exported file
   :return: FileInputStream that contains zip file

delete
^^^^^^

.. java:method::  void delete(String module)
   :outertype: ConfigurationService

   Deletes the db record corresponding to the module.

deleteByBundle
^^^^^^^^^^^^^^

.. java:method::  void deleteByBundle(String module)
   :outertype: ConfigurationService

   Deletes the db record corresponding to the module with given bundle symbolic name.

evictMotechSettingsCache
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void evictMotechSettingsCache()
   :outertype: ConfigurationService

getAllModuleProperties
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  Map<String, Properties> getAllModuleProperties(String module, Map<String, Properties> defaultProperties) throws IOException
   :outertype: ConfigurationService

   Retrieves all the module properties and returns them as Map, where key is the filename.

   :param module: The module we wish to retrieve properties for
   :param defaultProperties: Default properties of the module
   :return: Properties mapped by filename

getConfigSource
^^^^^^^^^^^^^^^

.. java:method::  ConfigSource getConfigSource()
   :outertype: ConfigurationService

   This method allows to check whether MOTECH is currently running in the FILE or UI mode

   :return: Current Config Source

getModuleProperties
^^^^^^^^^^^^^^^^^^^

.. java:method::  Properties getModuleProperties(String module, String filename, Properties defaultProperties) throws IOException
   :outertype: ConfigurationService

   Retrieves merged properties, given default set. Depending on the ConfigSource, it will either merge default properties with the properties from DB or get properties from file.

   :param module: The module we wish to retrieve properties for
   :param filename: Resource filename
   :param defaultProperties: Default properties of the module
   :return: Merged properties of the certain module

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method::  MotechSettings getPlatformSettings()
   :outertype: ConfigurationService

getRawConfig
^^^^^^^^^^^^

.. java:method::  InputStream getRawConfig(String module, String filename, Resource resource) throws IOException
   :outertype: ConfigurationService

   Allows to retrieve raw JSON data either from the database or file, depending on the specified ConfigSource mode.

   :param module: Module we wish to retrieve raw data for
   :param filename: Resource filename
   :param resource: Resource file containing default rawConfig, in case no other has been found
   :return: Raw JSON data as InputStream

listRawConfigNames
^^^^^^^^^^^^^^^^^^

.. java:method::  List<String> listRawConfigNames(String module)
   :outertype: ConfigurationService

   Depending on the selected ConfigSource mode, this method looks for all registered raw data properties within the specified module.

   :param module: Module we wish to perform look for
   :return: List of filenames that register raw config for specified module

loadBootstrapConfig
^^^^^^^^^^^^^^^^^^^

.. java:method::  BootstrapConfig loadBootstrapConfig()
   :outertype: ConfigurationService

   Loads bootstrap config that is used to start up the Motech server.

   The bootstrap configuration is loaded in the following order:

   ..

   #. Load the configuration from \ ``bootstrap.properties``\  from the config directory specified by the environment variable \ ``MOTECH_CONFIG_DIR``\ . \ ``bootstrap.properties``\  contains the following properties:

      .. parsed-literal::

         db.url (Mandatory)
         db.username (If required)
         db.password (If required)
         tenant.id (Optional. Defaults to 'DEFAULT')
         config.source (Optional. Defaults to 'UI')

      An example \ ``bootstrap.properties``\  is given below:

      .. parsed-literal::

         db.url=http://localhost:5984
         db.username=motech
         db.password=motech
         tenant.id=MotherChildCare
         config.source=FILE

   #. If \ ``MOTECH_CONFIG_DIR``\  environment variable is \ **not**\  set, load the specific configuration values from the following environment variables:

      .. parsed-literal::

         MOTECH_DB_URL (Mandatory)
         MOTECH_DB_USERNAME (If required)
         MOTECH_DB_PASSWORD (If required)
         MOTECH_TENANT_ID (Optional. Defaults to 'DEFAULT')
         MOTECH_CONFIG_SOURCE (Optional. Defaults to 'UI')

   #. If \ ``MOTECH_DB_URL``\  environment is not set, load the configuration from \ ``bootstrap.properties``\  from the default MOTECH config directory specified in the file \ ``config-locations.properties``\ .

   :return: Bootstrap configuration

loadConfig
^^^^^^^^^^

.. java:method::  SettingsRecord loadConfig()
   :outertype: ConfigurationService

loadDefaultConfig
^^^^^^^^^^^^^^^^^

.. java:method::  SettingsRecord loadDefaultConfig()
   :outertype: ConfigurationService

processExistingConfigs
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void processExistingConfigs(List<File> files)
   :outertype: ConfigurationService

   Adds, updates, or deletes configurations in FILE mode only. Files are classified as either raw config or properties based on the extension of the file. Uses CouchDb's bulk operations.

   :param files: Files to read configuration from.

rawConfigExists
^^^^^^^^^^^^^^^

.. java:method::  boolean rawConfigExists(String module, String filename)
   :outertype: ConfigurationService

   Allows to check if raw data has been registered for specified module

   :param module: Module symbolic name
   :param filename: Resource filename
   :return: True if raw data exists for given parameters, false otherwise

registersProperties
^^^^^^^^^^^^^^^^^^^

.. java:method::  boolean registersProperties(String module, String filename)
   :outertype: ConfigurationService

   Checks if given module registers certain property file

   :param module: Module we wish to perform check for
   :param filename: Resource filename
   :return: True if properties exist, false otherwise

removeProperties
^^^^^^^^^^^^^^^^

.. java:method::  void removeProperties(String module, String filename)
   :outertype: ConfigurationService

   Removes properties for given module from database or file.

   :param module: The module we wish to remove properties for
   :param filename: Resource filename

requiresConfigurationFiles
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  boolean requiresConfigurationFiles()
   :outertype: ConfigurationService

retrieveRegisteredBundleNames
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<String> retrieveRegisteredBundleNames()
   :outertype: ConfigurationService

   Depending on the selected ConfigSource mode, this method looks for registered bundle properties and returns a list of files it has found

   :return: List of files with registered properties

save
^^^^

.. java:method::  void save(BootstrapConfig bootstrapConfig)
   :outertype: ConfigurationService

   Saves the given \ ``BootstrapConfig``\  in the \ ``bootstrap.properties``\  file located in default MOTECH config location. The default motech config location is specified in the file \ ``config-locations.properties``\ .

   :param bootstrapConfig: Bootstrap configuration.

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void savePlatformSettings(Properties settings)
   :outertype: ConfigurationService

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void savePlatformSettings(MotechSettings settings)
   :outertype: ConfigurationService

saveRawConfig
^^^^^^^^^^^^^

.. java:method::  void saveRawConfig(String module, String version, String bundle, String filename, InputStream rawData) throws IOException
   :outertype: ConfigurationService

   Allows persisting of raw json properties either in the database or file, depending on the selected ConfigSource mode.

   :param module: Module we wish to save properties for
   :param filename: Resource filename
   :param rawData: Raw JSON data to persist

setPlatformSetting
^^^^^^^^^^^^^^^^^^

.. java:method:: @CacheEvict  void setPlatformSetting(String key, String value)
   :outertype: ConfigurationService

updateConfigLocation
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updateConfigLocation(String newConfigLocation)
   :outertype: ConfigurationService

   Adds a new config location and restarts the monitor.

   :param newConfigLocation: New config location

updatePropertiesAfterReinstallation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updatePropertiesAfterReinstallation(String module, String version, String bundle, String filename, Properties defaultProperties, Properties newProperties) throws IOException
   :outertype: ConfigurationService

   Works similar to \ ``addOrUpdateProperties``\  but instead of just adding / updating properties checks database for any deprecated properties and removes to ensure that only current ones are available

   :param module: The module we wish to update properties for
   :param version: Version of updated bundle
   :param bundle: Symbolic name of updated bundle
   :param filename: Resource filename
   :param newProperties: New properties to store
   :param defaultProperties: Default properties of the module

