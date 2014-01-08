.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormatter

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.motechproject.server.web.dto ModuleMenu

.. java:import:: org.motechproject.server.web.form UserInfo

.. java:import:: org.motechproject.server.web.helper MenuBuilder

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.lang.management ManagementFactory

.. java:import:: java.util Locale

DashboardController
===================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class DashboardController

   Main application controller. Responsible for retrieving information shared across the UI of different modules. The view returned by this controller will embed the UI of the currently requested module.

Methods
-------
accessdenied
^^^^^^^^^^^^

.. java:method:: @RequestMapping public ModelAndView accessdenied(HttpServletRequest request)
   :outertype: DashboardController

getModuleMenu
^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public ModuleMenu getModuleMenu(HttpServletRequest request)
   :outertype: DashboardController

getTime
^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String getTime(HttpServletRequest request)
   :outertype: DashboardController

getUptime
^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public DateTime getUptime()
   :outertype: DashboardController

getUser
^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public UserInfo getUser(HttpServletRequest request)
   :outertype: DashboardController

index
^^^^^

.. java:method:: @RequestMapping public ModelAndView index(String moduleName, HttpServletRequest request)
   :outertype: DashboardController

