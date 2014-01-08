.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechRolesCouchdbImpl

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.repository AllMotechUsersCouchdbImpl

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContext

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

MotechUserServiceIT
===================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MotechUserServiceIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: MotechUserServiceIT

hasUserShouldReturnTrueOnlyIfUserExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void hasUserShouldReturnTrueOnlyIfUserExists()
   :outertype: MotechUserServiceIT

onStartUp
^^^^^^^^^

.. java:method:: @Before public void onStartUp()
   :outertype: MotechUserServiceIT

shouldActivateUser
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldActivateUser()
   :outertype: MotechUserServiceIT

shouldChangePassword
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldChangePassword()
   :outertype: MotechUserServiceIT

shouldCreateActiveUserByDefault
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateActiveUserByDefault()
   :outertype: MotechUserServiceIT

shouldCreateInActiveUser
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateInActiveUser()
   :outertype: MotechUserServiceIT

shouldNotActivateInvalidUser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotActivateInvalidUser()
   :outertype: MotechUserServiceIT

shouldNotChangePasswordWithoutOldPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotChangePasswordWithoutOldPassword()
   :outertype: MotechUserServiceIT

shouldReturnEmptyListOfRolesForNonExistentUser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnEmptyListOfRolesForNonExistentUser()
   :outertype: MotechUserServiceIT

shouldReturnPresenceOfAdminUser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnPresenceOfAdminUser()
   :outertype: MotechUserServiceIT

shouldThrowExceptionIfPasswordIsEmptyForRegister
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfPasswordIsEmptyForRegister()
   :outertype: MotechUserServiceIT

shouldThrowExceptionIfUserNameIsEmptyForRegister
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUserNameIsEmptyForRegister()
   :outertype: MotechUserServiceIT

shouldThrowExceptionIfUserNameIsEmptyForRegisterWithActiveInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUserNameIsEmptyForRegisterWithActiveInfo()
   :outertype: MotechUserServiceIT

shouldThrowExceptionIfUserNameisNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUserNameisNull()
   :outertype: MotechUserServiceIT

shouldValidateUserCredentials
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateUserCredentials()
   :outertype: MotechUserServiceIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: MotechUserServiceIT

testPasswordEncoding
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPasswordEncoding()
   :outertype: MotechUserServiceIT

testRegister
^^^^^^^^^^^^

.. java:method:: @Test public void testRegister()
   :outertype: MotechUserServiceIT

