.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.ex RoleHasUserException

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechRolesCouchdbImpl

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.repository AllMotechUsersCouchdbImpl

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util Locale

MotechRoleServiceIT
===================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MotechRoleServiceIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: MotechRoleServiceIT

onStartUp
^^^^^^^^^

.. java:method:: @Before public void onStartUp()
   :outertype: MotechRoleServiceIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: MotechRoleServiceIT

testCreate
^^^^^^^^^^

.. java:method:: @Test public void testCreate()
   :outertype: MotechRoleServiceIT

testDelete
^^^^^^^^^^

.. java:method:: @Test public void testDelete()
   :outertype: MotechRoleServiceIT

testShouldNotDeleteNondeletableRole
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldNotDeleteNondeletableRole()
   :outertype: MotechRoleServiceIT

testShouldNotDeleteRoleWithUsers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldNotDeleteRoleWithUsers()
   :outertype: MotechRoleServiceIT

