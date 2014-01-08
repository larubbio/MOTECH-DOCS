.. java:import:: org.apache.commons.codec.binary Base64

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http HttpStatus

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.client.methods HttpUriRequest

.. java:import:: org.apache.http.entity StringEntity

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.osgi.helper SecurityTestConfigBuilder

.. java:import:: org.motechproject.security.repository AllMotechSecurityRules

.. java:import:: org.motechproject.security.repository AllMotechSecurityRulesCouchdbImpl

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.motechproject.security.service MotechProxyManager

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils PollingHttpClient

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.security.web FilterChainProxy

.. java:import:: org.springframework.web.context WebApplicationContext

.. java:import:: java.io IOException

.. java:import:: java.io UnsupportedEncodingException

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Locale

WebSecurityBundleIT
===================

.. java:package:: org.motechproject.security.osgi
   :noindex:

.. java:type:: public class WebSecurityBundleIT extends BaseOsgiIT

   Test class that verifies the web security services and dynamic security configuration. Stops and starts the web security bundle and makes HTTP requests with various credentials to test different permutations of dynamic security.

Methods
-------
getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: WebSecurityBundleIT

onSetUp
^^^^^^^

.. java:method:: @Override public void onSetUp() throws InterruptedException
   :outertype: WebSecurityBundleIT

onTearDown
^^^^^^^^^^

.. java:method:: @Override public void onTearDown() throws InterruptedException
   :outertype: WebSecurityBundleIT

testDynamicPermissionAccessSecurity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testDynamicPermissionAccessSecurity() throws InterruptedException, IOException, BundleException
   :outertype: WebSecurityBundleIT

testDynamicUserAccessSecurity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testDynamicUserAccessSecurity() throws InterruptedException, IOException, BundleException
   :outertype: WebSecurityBundleIT

testMethodSpecificSecurity
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testMethodSpecificSecurity() throws InterruptedException, IOException, BundleException
   :outertype: WebSecurityBundleIT

testProxyInitialization
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testProxyInitialization() throws Exception
   :outertype: WebSecurityBundleIT

testUpdatingProxyOnRestart
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testUpdatingProxyOnRestart() throws InterruptedException, BundleException, IOException, ClassNotFoundException
   :outertype: WebSecurityBundleIT

testWebSecurityServices
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testWebSecurityServices() throws Exception
   :outertype: WebSecurityBundleIT

