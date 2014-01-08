.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util Arrays

RoleControllerTest
==================

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: public class RoleControllerTest

Methods
-------
before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: RoleControllerTest

shouldGetRoleDetailsGivenItsName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetRoleDetailsGivenItsName() throws Exception
   :outertype: RoleControllerTest

