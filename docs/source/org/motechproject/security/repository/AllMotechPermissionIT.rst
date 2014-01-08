.. java:import:: ch.lambdaj Lambda

.. java:import:: org.hamcrest.beans HasPropertyWithValue

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: org.motechproject.security.domain MotechPermissionCouchdbImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util List

AllMotechPermissionIT
=====================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllMotechPermissionIT

Methods
-------
findByPermissionName
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void findByPermissionName()
   :outertype: AllMotechPermissionIT

setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: AllMotechPermissionIT

shouldDeletePermissions
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeletePermissions()
   :outertype: AllMotechPermissionIT

shouldNotCreateNewPermissionIfPermissionAlreadyExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotCreateNewPermissionIfPermissionAlreadyExists()
   :outertype: AllMotechPermissionIT

