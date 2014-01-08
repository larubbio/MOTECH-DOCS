.. java:import:: org.joda.time DateTime

.. java:import:: java.io IOException

.. java:import:: java.security DigestInputStream

.. java:import:: java.util Properties

MotechSettings
==============

.. java:package:: org.motechproject.server.config.domain
   :noindex:

.. java:type:: public interface MotechSettings

   Interface for main motech settings managment

Methods
-------
getActivemqProperties
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  Properties getActivemqProperties()
   :outertype: MotechSettings

getConfigFileChecksum
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  byte[] getConfigFileChecksum()
   :outertype: MotechSettings

getFilePath
^^^^^^^^^^^

.. java:method::  String getFilePath()
   :outertype: MotechSettings

getLanguage
^^^^^^^^^^^

.. java:method::  String getLanguage()
   :outertype: MotechSettings

getLastRun
^^^^^^^^^^

.. java:method::  DateTime getLastRun()
   :outertype: MotechSettings

getLoginMode
^^^^^^^^^^^^

.. java:method::  LoginMode getLoginMode()
   :outertype: MotechSettings

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method::  Properties getPlatformSettings()
   :outertype: MotechSettings

getProviderName
^^^^^^^^^^^^^^^

.. java:method::  String getProviderName()
   :outertype: MotechSettings

getProviderUrl
^^^^^^^^^^^^^^

.. java:method::  String getProviderUrl()
   :outertype: MotechSettings

getServerHost
^^^^^^^^^^^^^

.. java:method::  String getServerHost()
   :outertype: MotechSettings

getServerUrl
^^^^^^^^^^^^

.. java:method::  String getServerUrl()
   :outertype: MotechSettings

getStatusMsgTimeout
^^^^^^^^^^^^^^^^^^^

.. java:method::  String getStatusMsgTimeout()
   :outertype: MotechSettings

getUploadSize
^^^^^^^^^^^^^

.. java:method::  String getUploadSize()
   :outertype: MotechSettings

isPlatformInitialized
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  boolean isPlatformInitialized()
   :outertype: MotechSettings

load
^^^^

.. java:method::  void load(DigestInputStream dis) throws IOException
   :outertype: MotechSettings

savePlatformSetting
^^^^^^^^^^^^^^^^^^^

.. java:method::  void savePlatformSetting(String key, String value)
   :outertype: MotechSettings

setConfigFileChecksum
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void setConfigFileChecksum(byte[] configFileChecksum)
   :outertype: MotechSettings

setFilePath
^^^^^^^^^^^

.. java:method::  void setFilePath(String filePath)
   :outertype: MotechSettings

setLanguage
^^^^^^^^^^^

.. java:method::  void setLanguage(String language)
   :outertype: MotechSettings

setLastRun
^^^^^^^^^^

.. java:method::  void setLastRun(DateTime lastRun)
   :outertype: MotechSettings

setLoginModeValue
^^^^^^^^^^^^^^^^^

.. java:method::  void setLoginModeValue(String loginMode)
   :outertype: MotechSettings

setPlatformInitialized
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void setPlatformInitialized(boolean platformInitialized)
   :outertype: MotechSettings

setProviderName
^^^^^^^^^^^^^^^

.. java:method::  void setProviderName(String providerName)
   :outertype: MotechSettings

setProviderUrl
^^^^^^^^^^^^^^

.. java:method::  void setProviderUrl(String providerUrl)
   :outertype: MotechSettings

setServerUrl
^^^^^^^^^^^^

.. java:method::  void setServerUrl(String serverUrl)
   :outertype: MotechSettings

setStatusMsgTimeout
^^^^^^^^^^^^^^^^^^^

.. java:method::  void setStatusMsgTimeout(String statusMsgTimeout)
   :outertype: MotechSettings

setUploadSize
^^^^^^^^^^^^^

.. java:method::  void setUploadSize(String uploadSize)
   :outertype: MotechSettings

updateFromProperties
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updateFromProperties(Properties props)
   :outertype: MotechSettings

updateSettings
^^^^^^^^^^^^^^

.. java:method::  void updateSettings(SettingsRecord settingsRecord)
   :outertype: MotechSettings

