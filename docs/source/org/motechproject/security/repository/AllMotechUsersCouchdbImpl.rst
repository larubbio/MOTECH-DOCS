.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain MotechUserCouchdbImpl

.. java:import:: org.motechproject.security.ex EmailExistsException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllMotechUsersCouchdbImpl
=========================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @Component @View public class AllMotechUsersCouchdbImpl extends MotechBaseRepository<MotechUserCouchdbImpl> implements AllMotechUsers

Constructors
------------
AllMotechUsersCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllMotechUsersCouchdbImpl(CouchDbConnector db)
   :outertype: AllMotechUsersCouchdbImpl

Methods
-------
add
^^^

.. java:method:: @Override public void add(MotechUser user)
   :outertype: AllMotechUsersCouchdbImpl

addOpenIdUser
^^^^^^^^^^^^^

.. java:method:: @Override public void addOpenIdUser(MotechUser user)
   :outertype: AllMotechUsersCouchdbImpl

checkUserAuthorisation
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean checkUserAuthorisation(String userName, String password)
   :outertype: AllMotechUsersCouchdbImpl

findByRole
^^^^^^^^^^

.. java:method:: @Override @View public List<? extends MotechUser> findByRole(String role)
   :outertype: AllMotechUsersCouchdbImpl

findByUserName
^^^^^^^^^^^^^^

.. java:method:: @Override @View public MotechUser findByUserName(String userName)
   :outertype: AllMotechUsersCouchdbImpl

findUserByEmail
^^^^^^^^^^^^^^^

.. java:method:: @Override @View public MotechUser findUserByEmail(String email)
   :outertype: AllMotechUsersCouchdbImpl

findUserByOpenId
^^^^^^^^^^^^^^^^

.. java:method:: @Override @View public MotechUser findUserByOpenId(String openId)
   :outertype: AllMotechUsersCouchdbImpl

getOpenIdUsers
^^^^^^^^^^^^^^

.. java:method:: @Override public List<MotechUser> getOpenIdUsers()
   :outertype: AllMotechUsersCouchdbImpl

getUsers
^^^^^^^^

.. java:method:: @Override public List<MotechUser> getUsers()
   :outertype: AllMotechUsersCouchdbImpl

remove
^^^^^^

.. java:method:: @Override public void remove(MotechUser motechUser)
   :outertype: AllMotechUsersCouchdbImpl

update
^^^^^^

.. java:method:: @Override public void update(MotechUser motechUser)
   :outertype: AllMotechUsersCouchdbImpl

