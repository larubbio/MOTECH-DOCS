.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.web.controllers PermissionController

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.access AccessDeniedException

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

PermissionControllerSecurityIT
==============================

.. java:package:: org.motechproject.security.web.controllers.it
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class PermissionControllerSecurityIT

Methods
-------
after
^^^^^

.. java:method:: @After public void after()
   :outertype: PermissionControllerSecurityIT

shouldAllowCreationOfPermissionWithoutException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowCreationOfPermissionWithoutException()
   :outertype: PermissionControllerSecurityIT

shouldAllowDeleteOfPermissionWithoutException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAllowDeleteOfPermissionWithoutException()
   :outertype: PermissionControllerSecurityIT

shouldNotAllowCreationOfPermission
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowCreationOfPermission()
   :outertype: PermissionControllerSecurityIT

shouldNotAllowDeletionOfPermission
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowDeletionOfPermission()
   :outertype: PermissionControllerSecurityIT

shouldNotAllowViewingOfPermissions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowViewingOfPermissions()
   :outertype: PermissionControllerSecurityIT

