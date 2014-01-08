.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io Resource

.. java:import:: javax.annotation PostConstruct

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

SettingsFacade
==============

.. java:package:: org.motechproject.server.config
   :noindex:

.. java:type:: public class SettingsFacade

   SettingsFacade provides an interface to access application configuration present in files or database

Methods
-------
afterPropertiesSet
^^^^^^^^^^^^^^^^^^

.. java:method:: @PostConstruct public void afterPropertiesSet()
   :outertype: SettingsFacade

areConfigurationSettingsRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean areConfigurationSettingsRegistered()
   :outertype: SettingsFacade

asProperties
^^^^^^^^^^^^

.. java:method:: public Properties asProperties()
   :outertype: SettingsFacade

constructSymbolicName
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected String constructSymbolicName()
   :outertype: SettingsFacade

findFilename
^^^^^^^^^^^^

.. java:method:: protected String findFilename(String key)
   :outertype: SettingsFacade

getActivemqConfig
^^^^^^^^^^^^^^^^^

.. java:method:: public Properties getActivemqConfig()
   :outertype: SettingsFacade

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: SettingsFacade

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method:: public MotechSettings getPlatformSettings()
   :outertype: SettingsFacade

getProperties
^^^^^^^^^^^^^

.. java:method:: public Properties getProperties(String filename)
   :outertype: SettingsFacade

getProperty
^^^^^^^^^^^

.. java:method:: public String getProperty(String key)
   :outertype: SettingsFacade

getProperty
^^^^^^^^^^^

.. java:method:: public String getProperty(String key, String filename)
   :outertype: SettingsFacade

getRawConfig
^^^^^^^^^^^^

.. java:method:: public InputStream getRawConfig(String filename)
   :outertype: SettingsFacade

getResourceFileName
^^^^^^^^^^^^^^^^^^^

.. java:method:: protected static String getResourceFileName(Resource resource)
   :outertype: SettingsFacade

getSymbolicName
^^^^^^^^^^^^^^^

.. java:method:: public String getSymbolicName()
   :outertype: SettingsFacade

registerAllProperties
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void registerAllProperties()
   :outertype: SettingsFacade

registerAllRawConfig
^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void registerAllRawConfig()
   :outertype: SettingsFacade

registerProperties
^^^^^^^^^^^^^^^^^^

.. java:method:: protected void registerProperties(String filename, Properties properties)
   :outertype: SettingsFacade

saveConfigProperties
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void saveConfigProperties(String filename, Properties properties)
   :outertype: SettingsFacade

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void savePlatformSettings(MotechSettings settings)
   :outertype: SettingsFacade

saveRawConfig
^^^^^^^^^^^^^

.. java:method:: public void saveRawConfig(String filename, Resource resource)
   :outertype: SettingsFacade

setConfigFiles
^^^^^^^^^^^^^^

.. java:method:: public void setConfigFiles(List<Resource> resources)
   :outertype: SettingsFacade

setConfigurationService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setConfigurationService(ConfigurationService configurationService)
   :outertype: SettingsFacade

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: SettingsFacade

setProperty
^^^^^^^^^^^

.. java:method:: public void setProperty(String key, String value)
   :outertype: SettingsFacade

setRawConfigFiles
^^^^^^^^^^^^^^^^^

.. java:method:: public void setRawConfigFiles(List<Resource> resources)
   :outertype: SettingsFacade

unregisterProperties
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void unregisterProperties(String symbolicName)
   :outertype: SettingsFacade

