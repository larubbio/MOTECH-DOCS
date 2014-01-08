.. java:import:: org.motechproject.admin.domain AdminSettings

.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util List

SettingsService
===============

.. java:package:: org.motechproject.admin.service
   :noindex:

.. java:type:: public interface SettingsService

   Settings service used to manage platform setting changes from Admin interface.

Methods
-------
addSettingsPath
^^^^^^^^^^^^^^^

.. java:method::  void addSettingsPath(String path) throws IOException
   :outertype: SettingsService

exportConfig
^^^^^^^^^^^^

.. java:method::  InputStream exportConfig(String fileName) throws IOException
   :outertype: SettingsService

getBundleSettings
^^^^^^^^^^^^^^^^^

.. java:method::  List<Settings> getBundleSettings(long bundleId) throws IOException
   :outertype: SettingsService

getRawFilenames
^^^^^^^^^^^^^^^

.. java:method::  List<String> getRawFilenames(long bundleId)
   :outertype: SettingsService

getSettings
^^^^^^^^^^^

.. java:method::  AdminSettings getSettings()
   :outertype: SettingsService

retrieveRegisteredBundleNames
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<String> retrieveRegisteredBundleNames()
   :outertype: SettingsService

saveBundleSettings
^^^^^^^^^^^^^^^^^^

.. java:method::  void saveBundleSettings(Settings settings, long bundleId)
   :outertype: SettingsService

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void savePlatformSettings(Settings settings)
   :outertype: SettingsService

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void savePlatformSettings(List<Settings> settings)
   :outertype: SettingsService

saveRawFile
^^^^^^^^^^^

.. java:method::  void saveRawFile(MultipartFile file, String filename, long bundleId)
   :outertype: SettingsService

saveSettingsFile
^^^^^^^^^^^^^^^^

.. java:method::  void saveSettingsFile(MultipartFile configFile)
   :outertype: SettingsService

