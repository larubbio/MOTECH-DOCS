.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service SecurityRoleLoader

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.util Collections

SecurityRoleLoaderTest
======================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public class SecurityRoleLoaderTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: SecurityRoleLoaderTest

shouldCreateNewRoles
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateNewRoles() throws IOException
   :outertype: SecurityRoleLoaderTest

shouldDoNothingForNotExistingResources
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDoNothingForNotExistingResources()
   :outertype: SecurityRoleLoaderTest

shouldUpdateExistingRoles
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdateExistingRoles() throws IOException
   :outertype: SecurityRoleLoaderTest

