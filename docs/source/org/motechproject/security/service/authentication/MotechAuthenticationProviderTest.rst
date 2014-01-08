.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain MotechUserCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.service AuthoritiesService

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core AuthenticationException

.. java:import:: org.springframework.security.core.userdetails UserDetails

.. java:import:: java.util Locale

MotechAuthenticationProviderTest
================================

.. java:package:: org.motechproject.security.service.authentication
   :noindex:

.. java:type:: public class MotechAuthenticationProviderTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: MotechAuthenticationProviderTest

shouldAuthenticateUser
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAuthenticateUser()
   :outertype: MotechAuthenticationProviderTest

shouldNotAuthenticateEmptyPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAuthenticateEmptyPassword()
   :outertype: MotechAuthenticationProviderTest

shouldNotAuthenticateWrongPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAuthenticateWrongPassword()
   :outertype: MotechAuthenticationProviderTest

shouldRetrieveUserFromDatabase
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRetrieveUserFromDatabase()
   :outertype: MotechAuthenticationProviderTest

shouldThrowExceptionIfUserDoesntExist
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUserDoesntExist()
   :outertype: MotechAuthenticationProviderTest

shouldThrowExceptionIfUserIsInactive
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUserIsInactive()
   :outertype: MotechAuthenticationProviderTest

