.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web SubmenuInfo

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.dto ModuleMenu

.. java:import:: org.motechproject.server.web.dto ModuleMenuLink

.. java:import:: org.motechproject.server.web.dto ModuleMenuSection

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util Collection

.. java:import:: java.util List

.. java:import:: java.util Map

MenuBuilder
===========

.. java:package:: org.motechproject.server.web.helper
   :noindex:

.. java:type:: @Component public class MenuBuilder

   Helper class for building the modules menu view(left-hand side nav). Modules to display are retrieved from the \ :java:ref:`UIFrameworkService`\ . Filters entries based on user permissions.

Methods
-------
buildMenu
^^^^^^^^^

.. java:method:: public ModuleMenu buildMenu(String username)
   :outertype: MenuBuilder

   Builds the menu for the given user. Modules are retrieved from \ ``UIFrameworkService``\  and filtered based on permissions.

   :param username: username of the user for which the menu should be built.
   :return: the built menu object.

