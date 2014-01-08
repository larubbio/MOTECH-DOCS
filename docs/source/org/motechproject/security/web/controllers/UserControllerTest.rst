.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.mockito.internal.matchers Contains

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core.authority SimpleGrantedAuthority

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util Arrays

UserControllerTest
==================

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: public class UserControllerTest

Methods
-------
before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: UserControllerTest

shouldReturnCurrentUserDetails
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnCurrentUserDetails() throws Exception
   :outertype: UserControllerTest

