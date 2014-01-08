.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.osgi.web Header

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web SubmenuInfo

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.osgi.web.ext ApplicationEnvironment

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.dto ModuleMenu

.. java:import:: org.motechproject.server.web.dto ModuleMenuLink

.. java:import:: org.motechproject.server.web.dto ModuleMenuSection

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: java.util Arrays

.. java:import:: java.util Collection

.. java:import:: java.util Dictionary

.. java:import:: java.util HashMap

.. java:import:: java.util Hashtable

.. java:import:: java.util List

.. java:import:: java.util Map

MenuBuilderTest
===============

.. java:package:: org.motechproject.server.web.helper
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class MenuBuilderTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: MenuBuilderTest

shouldBuildMenuWithAllLinks
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBuildMenuWithAllLinks()
   :outertype: MenuBuilderTest

shouldFilterMenuBasedOnRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFilterMenuBasedOnRoles()
   :outertype: MenuBuilderTest

shouldNotAddLinksForSubMenusForWhichUserDoesNotHaveRequisiteRole
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAddLinksForSubMenusForWhichUserDoesNotHaveRequisiteRole()
   :outertype: MenuBuilderTest

shouldNotAddMenuSectionIfUserDoesNotHaveAccessToAnySubMenu
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAddMenuSectionIfUserDoesNotHaveAccessToAnySubMenu()
   :outertype: MenuBuilderTest

