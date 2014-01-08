.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Assert

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentMatcher

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.motechproject.server.web.dto StartupViewData

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: org.motechproject.server.web.form StartupSuggestionsForm

.. java:import:: org.motechproject.server.web.helper SuggestionHelper

.. java:import:: org.motechproject.server.web.validator StartupFormValidatorFactory

.. java:import:: org.springframework.validation BindingResult

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.io IOException

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

.. java:import:: java.util NavigableMap

.. java:import:: java.util Properties

.. java:import:: java.util TreeMap

StartupControllerTest
=====================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: public class StartupControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: StartupControllerTest

shouldAddErrorsWhenValidationFails
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddErrorsWhenValidationFails() throws IOException
   :outertype: StartupControllerTest

shouldAddFlagIndicatingAbsenceOfAdminUser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddFlagIndicatingAbsenceOfAdminUser()
   :outertype: StartupControllerTest

shouldInformViewThatConfigFilesNotRequiredWhenConfigSourceIsFileAndConfigFilesExist
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldInformViewThatConfigFilesNotRequiredWhenConfigSourceIsFileAndConfigFilesExist() throws IOException
   :outertype: StartupControllerTest

shouldInformViewThatConfigFilesNotRequiredWhenConfigSourceIsUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldInformViewThatConfigFilesNotRequiredWhenConfigSourceIsUI() throws IOException
   :outertype: StartupControllerTest

shouldInformViewThatConfigFilesRequiredWhenConfigSourceIsFileAndConfigFilesDoNotExist
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldInformViewThatConfigFilesRequiredWhenConfigSourceIsFileAndConfigFilesDoNotExist() throws IOException
   :outertype: StartupControllerTest

shouldNotAllowStartupPostAfterStartup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowStartupPostAfterStartup() throws IOException
   :outertype: StartupControllerTest

shouldNotRegisterAdminUserIfActiveAdminUserAlreadyExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterAdminUserIfActiveAdminUserAlreadyExists() throws IOException
   :outertype: StartupControllerTest

testStartup
^^^^^^^^^^^

.. java:method:: @Test public void testStartup()
   :outertype: StartupControllerTest

testStartupRedirectToHome
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testStartupRedirectToHome()
   :outertype: StartupControllerTest

testSubmitFormOpenId
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSubmitFormOpenId() throws IOException
   :outertype: StartupControllerTest

testSubmitFormStart
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSubmitFormStart() throws IOException
   :outertype: StartupControllerTest

