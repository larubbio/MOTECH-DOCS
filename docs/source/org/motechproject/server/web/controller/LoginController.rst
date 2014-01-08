.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.motechproject.server.web.dto LoginViewData

.. java:import:: org.motechproject.server.web.form LoginForm

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.servlet.http HttpServletRequest

LoginController
===============

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class LoginController

   Login Controller for user authentication.

Methods
-------
getLoginViewData
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public LoginViewData getLoginViewData(HttpServletRequest request)
   :outertype: LoginController

login
^^^^^

.. java:method:: @RequestMapping public ModelAndView login(HttpServletRequest request)
   :outertype: LoginController

