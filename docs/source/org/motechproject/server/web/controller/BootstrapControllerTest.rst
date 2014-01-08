.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito InOrder

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.web.form BootstrapConfigForm

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server MvcResult

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: org.springframework.test.web.server.setup StandaloneMockMvcBuilder

.. java:import:: org.springframework.validation BindingResult

.. java:import:: org.springframework.validation ObjectError

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: java.util Arrays

.. java:import:: java.util List

BootstrapControllerTest
=======================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class BootstrapControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: BootstrapControllerTest

shouldAddErrorOnSaveAndReturnTheSameBootstrapStartupView
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddErrorOnSaveAndReturnTheSameBootstrapStartupView() throws Exception
   :outertype: BootstrapControllerTest

shouldAddErrorsOnValidationFailure
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddErrorsOnValidationFailure() throws Exception
   :outertype: BootstrapControllerTest

shouldRedirectToHomePageIfBootstrapConfigIsAlreadyLoaded
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRedirectToHomePageIfBootstrapConfigIsAlreadyLoaded() throws Exception
   :outertype: BootstrapControllerTest

shouldReturnViewWithBootstrapFlagSet
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnViewWithBootstrapFlagSet() throws Exception
   :outertype: BootstrapControllerTest

shouldSaveBootstrapConfig
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveBootstrapConfig() throws Exception
   :outertype: BootstrapControllerTest

