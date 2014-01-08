.. java:import:: org.motechproject.security.ex UserNotFoundException

.. java:import:: org.motechproject.security.password NonAdminUserException

.. java:import:: org.motechproject.security.service PasswordRecoveryService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.web.dto ForgotViewData

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: org.springframework.web.servlet.i18n CookieLocaleResolver

.. java:import:: javax.servlet.http HttpServletRequest

ForgotController
================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class ForgotController

   Forgot Controller for reset password.

Methods
-------
forgotPost
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String forgotPost(String email)
   :outertype: ForgotController

getForgotViewData
^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public ForgotViewData getForgotViewData(HttpServletRequest request)
   :outertype: ForgotController

login
^^^^^

.. java:method:: @RequestMapping public ModelAndView login(HttpServletRequest request)
   :outertype: ForgotController

