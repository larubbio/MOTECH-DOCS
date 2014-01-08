.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.web.controllers RoleController

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.access AccessDeniedException

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util Collections

RoleControllerSecurityIT
========================

.. java:package:: org.motechproject.security.web.controllers.it
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class RoleControllerSecurityIT

Methods
-------
after
^^^^^

.. java:method:: @After public void after()
   :outertype: RoleControllerSecurityIT

shouldAllowRoleCreationWithoutException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowRoleCreationWithoutException()
   :outertype: RoleControllerSecurityIT

shouldAllowRoleDeletionWithoutException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowRoleDeletionWithoutException()
   :outertype: RoleControllerSecurityIT

shouldAllowRoleUpdateWithoutException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowRoleUpdateWithoutException()
   :outertype: RoleControllerSecurityIT

shouldAllowViewingAllRolesException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowViewingAllRolesException()
   :outertype: RoleControllerSecurityIT

shouldDenyRoleCreation
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDenyRoleCreation()
   :outertype: RoleControllerSecurityIT

shouldNotAllowRoleDeletion
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowRoleDeletion()
   :outertype: RoleControllerSecurityIT

shouldNotAllowRoleUpdate
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowRoleUpdate()
   :outertype: RoleControllerSecurityIT

shouldNotAllowRoles
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowRoles()
   :outertype: RoleControllerSecurityIT

