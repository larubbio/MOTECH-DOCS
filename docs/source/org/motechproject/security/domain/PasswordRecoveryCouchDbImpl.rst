.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: java.util Locale

PasswordRecoveryCouchDbImpl
===========================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class PasswordRecoveryCouchDbImpl extends MotechBaseDataObject implements PasswordRecovery

   CouchDb implementation of \ :java:ref:`PasswordRecovery`\ .

Fields
------
DOCTYPE
^^^^^^^

.. java:field:: public static final String DOCTYPE
   :outertype: PasswordRecoveryCouchDbImpl

Constructors
------------
PasswordRecoveryCouchDbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PasswordRecoveryCouchDbImpl()
   :outertype: PasswordRecoveryCouchDbImpl

Methods
-------
getEmail
^^^^^^^^

.. java:method:: @Override public String getEmail()
   :outertype: PasswordRecoveryCouchDbImpl

getExpirationDate
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public DateTime getExpirationDate()
   :outertype: PasswordRecoveryCouchDbImpl

getLocale
^^^^^^^^^

.. java:method:: @Override public Locale getLocale()
   :outertype: PasswordRecoveryCouchDbImpl

getToken
^^^^^^^^

.. java:method:: @Override public String getToken()
   :outertype: PasswordRecoveryCouchDbImpl

getUsername
^^^^^^^^^^^

.. java:method:: @Override public String getUsername()
   :outertype: PasswordRecoveryCouchDbImpl

setEmail
^^^^^^^^

.. java:method:: @Override public void setEmail(String email)
   :outertype: PasswordRecoveryCouchDbImpl

setExpirationDate
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setExpirationDate(DateTime expirationDate)
   :outertype: PasswordRecoveryCouchDbImpl

setLocale
^^^^^^^^^

.. java:method:: @Override public void setLocale(Locale locale)
   :outertype: PasswordRecoveryCouchDbImpl

setToken
^^^^^^^^

.. java:method:: @Override public void setToken(String token)
   :outertype: PasswordRecoveryCouchDbImpl

setUsername
^^^^^^^^^^^

.. java:method:: @Override public void setUsername(String username)
   :outertype: PasswordRecoveryCouchDbImpl

