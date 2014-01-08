.. java:import:: org.ektorp CouchDbInstance

.. java:import:: org.ektorp DbAccessException

.. java:import:: org.ektorp.http HttpClient

.. java:import:: org.ektorp.http StdHttpClient

.. java:import:: org.ektorp.impl StdCouchDbInstance

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.web.form BootstrapConfigForm

.. java:import:: org.motechproject.server.web.validator BootstrapConfigFormValidator

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.validation BindingResult

.. java:import:: org.springframework.validation ObjectError

.. java:import:: org.springframework.web.bind WebDataBinder

.. java:import:: org.springframework.web.bind.annotation InitBinder

.. java:import:: org.springframework.web.bind.annotation ModelAttribute

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.validation Valid

.. java:import:: java.net MalformedURLException

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

BootstrapController
===================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class BootstrapController

   controller for capturing bootstrap configuration from UI

Fields
------
BOOTSTRAP_CONFIG_VIEW
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String BOOTSTRAP_CONFIG_VIEW
   :outertype: BootstrapController

Methods
-------
bootstrapForm
^^^^^^^^^^^^^

.. java:method:: @RequestMapping public ModelAndView bootstrapForm()
   :outertype: BootstrapController

initBinder
^^^^^^^^^^

.. java:method:: @InitBinder protected void initBinder(WebDataBinder binder)
   :outertype: BootstrapController

submitForm
^^^^^^^^^^

.. java:method:: @RequestMapping public ModelAndView submitForm(BootstrapConfigForm form, BindingResult result)
   :outertype: BootstrapController

verifyConnection
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Map<String, ? extends Object> verifyConnection(BootstrapConfigForm form, BindingResult result)
   :outertype: BootstrapController

