.. java:import:: org.apache.commons.codec.binary Base64

.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http HttpStatus

.. java:import:: org.apache.http.client.methods HttpDelete

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.client.methods HttpUriRequest

.. java:import:: org.apache.http.entity StringEntity

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils PollingHttpClient

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.springframework.http MediaType

.. java:import:: java.io IOException

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

RolesBundleIT
=============

.. java:package:: org.motechproject.security.osgi
   :noindex:

.. java:type:: public class RolesBundleIT extends BaseOsgiIT

Fields
------
MANAGE_ROLE
^^^^^^^^^^^

.. java:field:: public static final String MANAGE_ROLE
   :outertype: RolesBundleIT

Methods
-------
getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: RolesBundleIT

onSetUp
^^^^^^^

.. java:method:: @Override public void onSetUp() throws InterruptedException
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToCreatePermission
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToCreatePermission() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToCreateRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToCreateRoles() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToDeletePermission
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToDeletePermission() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToDeleteRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToDeleteRoles() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToUpdateRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToUpdateRoles() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToViewPermissions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToViewPermissions() throws Exception
   :outertype: RolesBundleIT

testThatAccessIsDeniedForUnAuthorisedUserTryingToViewRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAccessIsDeniedForUnAuthorisedUserTryingToViewRoles() throws Exception
   :outertype: RolesBundleIT

testThatAuthorisedUserCanViewPermissions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAuthorisedUserCanViewPermissions() throws Exception
   :outertype: RolesBundleIT

testThatAuthorisedUserCanViewRoles
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatAuthorisedUserCanViewRoles() throws Exception
   :outertype: RolesBundleIT

testThatRoleThatAllowsRoleManagementIsPresent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatRoleThatAllowsRoleManagementIsPresent() throws InterruptedException
   :outertype: RolesBundleIT

