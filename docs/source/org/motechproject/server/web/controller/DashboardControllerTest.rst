.. java:import:: junit.framework Assert

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.startup StartupManager

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.motechproject.server.web.form UserInfo

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: javax.servlet ServletContext

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpSession

.. java:import:: java.security Principal

.. java:import:: java.util Locale

DashboardControllerTest
=======================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class DashboardControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: DashboardControllerTest

testDashboardNoModule
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testDashboardNoModule()
   :outertype: DashboardControllerTest

testDashboardWithModule
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testDashboardWithModule()
   :outertype: DashboardControllerTest

testGetUser
^^^^^^^^^^^

.. java:method:: @Test public void testGetUser()
   :outertype: DashboardControllerTest

