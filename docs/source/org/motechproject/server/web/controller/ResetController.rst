.. java:import:: org.motechproject.security.ex InvalidTokenException

.. java:import:: org.motechproject.security.service PasswordRecoveryService

.. java:import:: org.motechproject.server.web.dto ResetViewData

.. java:import:: org.motechproject.server.web.form ResetForm

.. java:import:: org.motechproject.server.web.validator ResetFormValidator

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

.. java:import:: java.util List

ResetController
===============

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class ResetController

Methods
-------
getResetViewData
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public ResetViewData getResetViewData(HttpServletRequest request)
   :outertype: ResetController

reset
^^^^^

.. java:method:: @RequestMapping @ResponseBody public ResetViewData reset(ResetForm form, HttpServletRequest request)
   :outertype: ResetController

resetView
^^^^^^^^^

.. java:method:: @RequestMapping public ModelAndView resetView(HttpServletRequest request)
   :outertype: ResetController

