.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentMatcher

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.security.domain PasswordRecoveryCouchDbImpl

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: org.motechproject.security.email EmailSender

.. java:import:: org.motechproject.security.email EmailSenderImpl

.. java:import:: org.motechproject.security.ex InvalidTokenException

.. java:import:: org.motechproject.security.ex UserNotFoundException

.. java:import:: org.motechproject.security.password NonAdminUserException

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.repository AllPasswordRecoveries

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.testing.utils BaseUnitTest

.. java:import:: org.apache.velocity.app VelocityEngine

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

PasswordRecoveryServiceTest
===========================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public class PasswordRecoveryServiceTest extends BaseUnitTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: PasswordRecoveryServiceTest

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: PasswordRecoveryServiceTest

testCleanUpExpired
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testCleanUpExpired()
   :outertype: PasswordRecoveryServiceTest

testCreateOpenIDRecovery
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testCreateOpenIDRecovery() throws UserNotFoundException, NonAdminUserException
   :outertype: PasswordRecoveryServiceTest

testCreateRecovery
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testCreateRecovery() throws UserNotFoundException
   :outertype: PasswordRecoveryServiceTest

testExpiredRequest
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testExpiredRequest() throws InvalidTokenException
   :outertype: PasswordRecoveryServiceTest

testInvalidToken
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testInvalidToken() throws InvalidTokenException
   :outertype: PasswordRecoveryServiceTest

testNoFindUserInOneTimeToken
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNoFindUserInOneTimeToken() throws UserNotFoundException, NonAdminUserException
   :outertype: PasswordRecoveryServiceTest

testNonAdminUserInOneTimeToken
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNonAdminUserInOneTimeToken() throws UserNotFoundException, NonAdminUserException
   :outertype: PasswordRecoveryServiceTest

testResetPassword
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testResetPassword() throws InvalidTokenException
   :outertype: PasswordRecoveryServiceTest

testSendRecoveryEmail
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSendRecoveryEmail()
   :outertype: PasswordRecoveryServiceTest

testUserNotFound
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testUserNotFound() throws UserNotFoundException
   :outertype: PasswordRecoveryServiceTest

testWrongConfirmation
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testWrongConfirmation() throws InvalidTokenException
   :outertype: PasswordRecoveryServiceTest

