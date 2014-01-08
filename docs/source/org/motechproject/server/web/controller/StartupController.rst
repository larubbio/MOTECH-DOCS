.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.motechproject.server.web.dto StartupViewData

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: org.motechproject.server.web.form StartupSuggestionsForm

.. java:import:: org.motechproject.server.web.helper SuggestionHelper

.. java:import:: org.motechproject.server.web.validator StartupFormValidator

.. java:import:: org.motechproject.server.web.validator StartupFormValidatorFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.io IOException

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

StartupController
=================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class StartupController

   StartupController that manages the platform system start up and captures the platform core settings and user information.

Methods
-------
getStartupViewData
^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public StartupViewData getStartupViewData(HttpServletRequest request)
   :outertype: StartupController

setStartupFormValidatorFactory
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setStartupFormValidatorFactory(StartupFormValidatorFactory validatorFactory)
   :outertype: StartupController

startup
^^^^^^^

.. java:method:: @RequestMapping public ModelAndView startup()
   :outertype: StartupController

submitForm
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<String> submitForm(StartupForm startupSettings) throws IOException
   :outertype: StartupController

