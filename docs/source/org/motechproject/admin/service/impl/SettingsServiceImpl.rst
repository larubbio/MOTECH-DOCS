.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.admin.domain AdminSettings

.. java:import:: org.motechproject.admin.service SettingsService

.. java:import:: org.motechproject.admin.settings ParamParser

.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: org.motechproject.admin.settings SettingsOption

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.monitor ConfigFileMonitor

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework Version

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net URL

.. java:import:: java.util ArrayList

.. java:import:: java.util Enumeration

.. java:import:: java.util HashMap

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

SettingsServiceImpl
===================

.. java:package:: org.motechproject.admin.service.impl
   :noindex:

.. java:type:: @Service public class SettingsServiceImpl implements SettingsService

   Implementation of \ :java:ref:`SettingsService`\  interface for settings management.

Methods
-------
addSettingsPath
^^^^^^^^^^^^^^^

.. java:method:: @Override public void addSettingsPath(String newConfigLocation) throws IOException
   :outertype: SettingsServiceImpl

exportConfig
^^^^^^^^^^^^

.. java:method:: @Override public InputStream exportConfig(String fileName) throws IOException
   :outertype: SettingsServiceImpl

getBundleSettings
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<Settings> getBundleSettings(long bundleId) throws IOException
   :outertype: SettingsServiceImpl

getRawFilenames
^^^^^^^^^^^^^^^

.. java:method:: @Override public List<String> getRawFilenames(long bundleId)
   :outertype: SettingsServiceImpl

getSettings
^^^^^^^^^^^

.. java:method:: @Override public AdminSettings getSettings()
   :outertype: SettingsServiceImpl

retrieveRegisteredBundleNames
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<String> retrieveRegisteredBundleNames()
   :outertype: SettingsServiceImpl

saveBundleSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void saveBundleSettings(Settings settings, long bundleId)
   :outertype: SettingsServiceImpl

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void savePlatformSettings(Settings settings)
   :outertype: SettingsServiceImpl

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void savePlatformSettings(List<Settings> settings)
   :outertype: SettingsServiceImpl

saveRawFile
^^^^^^^^^^^

.. java:method:: @Override public void saveRawFile(MultipartFile file, String filename, long bundleId)
   :outertype: SettingsServiceImpl

saveSettingsFile
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void saveSettingsFile(MultipartFile configFile)
   :outertype: SettingsServiceImpl

