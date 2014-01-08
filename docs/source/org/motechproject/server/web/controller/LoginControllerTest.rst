.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: org.springframework.web.servlet ModelAndView

LoginControllerTest
===================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class LoginControllerTest

Fields
------
loginController
^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  LoginController loginController
   :outertype: LoginControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: LoginControllerTest

shouldRedirectToBootstrapUIIfBootstrapConfigIsNotAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRedirectToBootstrapUIIfBootstrapConfigIsNotAvailable()
   :outertype: LoginControllerTest

testLogin
^^^^^^^^^

.. java:method:: @Test public void testLogin() throws Exception
   :outertype: LoginControllerTest

