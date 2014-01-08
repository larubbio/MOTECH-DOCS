.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support View

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: org.motechproject.security.domain PasswordRecoveryCouchDbImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Locale

AllPasswordRecoveriesCouchDbImpl
================================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @Repository @View public class AllPasswordRecoveriesCouchDbImpl extends MotechBaseRepository<PasswordRecoveryCouchDbImpl> implements AllPasswordRecoveries

Constructors
------------
AllPasswordRecoveriesCouchDbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllPasswordRecoveriesCouchDbImpl(CouchDbConnector db)
   :outertype: AllPasswordRecoveriesCouchDbImpl

Methods
-------
add
^^^

.. java:method:: @Override public void add(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveriesCouchDbImpl

allRecoveries
^^^^^^^^^^^^^

.. java:method:: @Override public List<PasswordRecovery> allRecoveries()
   :outertype: AllPasswordRecoveriesCouchDbImpl

createRecovery
^^^^^^^^^^^^^^

.. java:method:: @Override public PasswordRecovery createRecovery(String username, String email, String token, DateTime expirationDate, Locale locale)
   :outertype: AllPasswordRecoveriesCouchDbImpl

findForToken
^^^^^^^^^^^^

.. java:method:: @Override @View public PasswordRecovery findForToken(String token)
   :outertype: AllPasswordRecoveriesCouchDbImpl

findForUser
^^^^^^^^^^^

.. java:method:: @Override @View public PasswordRecovery findForUser(String username)
   :outertype: AllPasswordRecoveriesCouchDbImpl

getExpired
^^^^^^^^^^

.. java:method:: @Override public List<PasswordRecovery> getExpired()
   :outertype: AllPasswordRecoveriesCouchDbImpl

remove
^^^^^^

.. java:method:: @Override public void remove(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveriesCouchDbImpl

update
^^^^^^

.. java:method:: @Override public void update(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveriesCouchDbImpl

