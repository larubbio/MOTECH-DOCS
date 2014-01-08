.. java:import:: org.apache.commons.collections MapUtils

.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonIgnoreProperties

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api MotechMapUtils

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: java.io IOException

.. java:import:: java.security DigestInputStream

.. java:import:: java.util Arrays

.. java:import:: java.util Map

.. java:import:: java.util Objects

.. java:import:: java.util Properties

SettingsRecord
==============

.. java:package:: org.motechproject.server.config.domain
   :noindex:

.. java:type:: @TypeDiscriminator @JsonIgnoreProperties public class SettingsRecord extends MotechBaseDataObject implements MotechSettings

   Class for storing settings values

Methods
-------
getActivemqProperties
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Properties getActivemqProperties()
   :outertype: SettingsRecord

getConfigFileChecksum
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public byte[] getConfigFileChecksum()
   :outertype: SettingsRecord

getFilePath
^^^^^^^^^^^

.. java:method:: @Override public String getFilePath()
   :outertype: SettingsRecord

getLanguage
^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getLanguage()
   :outertype: SettingsRecord

getLastRun
^^^^^^^^^^

.. java:method:: @Override public DateTime getLastRun()
   :outertype: SettingsRecord

getLoginMode
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public LoginMode getLoginMode()
   :outertype: SettingsRecord

getLoginModeValue
^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getLoginModeValue()
   :outertype: SettingsRecord

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Properties getPlatformSettings()
   :outertype: SettingsRecord

getProviderName
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getProviderName()
   :outertype: SettingsRecord

getProviderUrl
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getProviderUrl()
   :outertype: SettingsRecord

getServerHost
^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getServerHost()
   :outertype: SettingsRecord

getServerUrl
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getServerUrl()
   :outertype: SettingsRecord

getStatusMsgTimeout
^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getStatusMsgTimeout()
   :outertype: SettingsRecord

getUploadSize
^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getUploadSize()
   :outertype: SettingsRecord

isPlatformInitialized
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean isPlatformInitialized()
   :outertype: SettingsRecord

load
^^^^

.. java:method:: @Override public synchronized void load(DigestInputStream dis) throws IOException
   :outertype: SettingsRecord

mergeWithDefaults
^^^^^^^^^^^^^^^^^

.. java:method:: public void mergeWithDefaults(Properties defaultConfig)
   :outertype: SettingsRecord

removeDefaults
^^^^^^^^^^^^^^

.. java:method:: public void removeDefaults(Properties defaultConfig)
   :outertype: SettingsRecord

savePlatformSetting
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void savePlatformSetting(String key, String value)
   :outertype: SettingsRecord

setConfigFileChecksum
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setConfigFileChecksum(byte[] configFileChecksum)
   :outertype: SettingsRecord

setFilePath
^^^^^^^^^^^

.. java:method:: @Override public void setFilePath(String filePath)
   :outertype: SettingsRecord

setLanguage
^^^^^^^^^^^

.. java:method:: @Override public void setLanguage(String language)
   :outertype: SettingsRecord

setLastRun
^^^^^^^^^^

.. java:method:: @Override public void setLastRun(DateTime lastRun)
   :outertype: SettingsRecord

setLoginModeValue
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setLoginModeValue(String loginMode)
   :outertype: SettingsRecord

setPlatformInitialized
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setPlatformInitialized(boolean platformInitialized)
   :outertype: SettingsRecord

setProviderName
^^^^^^^^^^^^^^^

.. java:method:: @Override public void setProviderName(String providerName)
   :outertype: SettingsRecord

setProviderUrl
^^^^^^^^^^^^^^

.. java:method:: @Override public void setProviderUrl(String providerUrl)
   :outertype: SettingsRecord

setServerUrl
^^^^^^^^^^^^

.. java:method:: @Override public void setServerUrl(String serverUrl)
   :outertype: SettingsRecord

setStatusMsgTimeout
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setStatusMsgTimeout(String statusMsgTimeout)
   :outertype: SettingsRecord

setUploadSize
^^^^^^^^^^^^^

.. java:method:: @Override public void setUploadSize(String uploadSize)
   :outertype: SettingsRecord

updateFromProperties
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateFromProperties(Properties props)
   :outertype: SettingsRecord

updateSettings
^^^^^^^^^^^^^^

.. java:method:: @Override public void updateSettings(SettingsRecord settingsRecord)
   :outertype: SettingsRecord

