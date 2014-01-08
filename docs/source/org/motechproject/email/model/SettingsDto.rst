.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: java.util Objects

.. java:import:: java.util Properties

SettingsDto
===========

.. java:package:: org.motechproject.email.model
   :noindex:

.. java:type:: public class SettingsDto

Fields
------
EMAIL_PROPERTIES_FILE_NAME
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String EMAIL_PROPERTIES_FILE_NAME
   :outertype: SettingsDto

MAIL_HOST_PROPERTY
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_HOST_PROPERTY
   :outertype: SettingsDto

MAIL_LOG_ADDRESS_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_ADDRESS_PROPERTY
   :outertype: SettingsDto

MAIL_LOG_BODY_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_BODY_PROPERTY
   :outertype: SettingsDto

MAIL_LOG_PURGE_ENABLE_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_PURGE_ENABLE_PROPERTY
   :outertype: SettingsDto

MAIL_LOG_PURGE_TIME_MULTIPLIER_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_PURGE_TIME_MULTIPLIER_PROPERTY
   :outertype: SettingsDto

MAIL_LOG_PURGE_TIME_PROPERY
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_PURGE_TIME_PROPERY
   :outertype: SettingsDto

MAIL_LOG_SUBJECT_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_LOG_SUBJECT_PROPERTY
   :outertype: SettingsDto

MAIL_PORT_PROPERTY
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAIL_PORT_PROPERTY
   :outertype: SettingsDto

Constructors
------------
SettingsDto
^^^^^^^^^^^

.. java:constructor:: public SettingsDto()
   :outertype: SettingsDto

SettingsDto
^^^^^^^^^^^

.. java:constructor:: public SettingsDto(SettingsFacade settingsFacade)
   :outertype: SettingsDto

SettingsDto
^^^^^^^^^^^

.. java:constructor:: public SettingsDto(String host, String port, String logAddress, String logSubject, String logBody, String logPurgeEnable)
   :outertype: SettingsDto

SettingsDto
^^^^^^^^^^^

.. java:constructor:: public SettingsDto(String host, String port, String logAddress, String logSubject, String logBody, String logPurgeEnable, String logPurgeTime, String logPurgeTimeMultiplier)
   :outertype: SettingsDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: SettingsDto

getHost
^^^^^^^

.. java:method:: public String getHost()
   :outertype: SettingsDto

getLogAddress
^^^^^^^^^^^^^

.. java:method:: public String getLogAddress()
   :outertype: SettingsDto

getLogBody
^^^^^^^^^^

.. java:method:: public String getLogBody()
   :outertype: SettingsDto

getLogPurgeEnable
^^^^^^^^^^^^^^^^^

.. java:method:: public String getLogPurgeEnable()
   :outertype: SettingsDto

getLogPurgeTime
^^^^^^^^^^^^^^^

.. java:method:: public String getLogPurgeTime()
   :outertype: SettingsDto

getLogPurgeTimeMultiplier
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getLogPurgeTimeMultiplier()
   :outertype: SettingsDto

getLogSubject
^^^^^^^^^^^^^

.. java:method:: public String getLogSubject()
   :outertype: SettingsDto

getPort
^^^^^^^

.. java:method:: public String getPort()
   :outertype: SettingsDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: SettingsDto

setHost
^^^^^^^

.. java:method:: public void setHost(String host)
   :outertype: SettingsDto

setLogAddress
^^^^^^^^^^^^^

.. java:method:: public void setLogAddress(String logAddress)
   :outertype: SettingsDto

setLogBody
^^^^^^^^^^

.. java:method:: public void setLogBody(String logBody)
   :outertype: SettingsDto

setLogPurgeEnable
^^^^^^^^^^^^^^^^^

.. java:method:: public void setLogPurgeEnable(String logPurgeEnable)
   :outertype: SettingsDto

setLogPurgeTime
^^^^^^^^^^^^^^^

.. java:method:: public void setLogPurgeTime(String logPurgeTime)
   :outertype: SettingsDto

setLogPurgeTimeMultiplier
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setLogPurgeTimeMultiplier(String logPurgeTimeMultiplier)
   :outertype: SettingsDto

setLogSubject
^^^^^^^^^^^^^

.. java:method:: public void setLogSubject(String logSubject)
   :outertype: SettingsDto

setPort
^^^^^^^

.. java:method:: public void setPort(String port)
   :outertype: SettingsDto

toProperties
^^^^^^^^^^^^

.. java:method:: public Properties toProperties()
   :outertype: SettingsDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: SettingsDto

