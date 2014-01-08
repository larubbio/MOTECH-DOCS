.. java:import:: ch.lambdaj Lambda

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http NameValuePair

.. java:import:: org.apache.http.client.entity UrlEncodedFormEntity

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.impl.client BasicResponseHandler

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.apache.http.message BasicNameValuePair

.. java:import:: org.apache.http.util EntityUtils

.. java:import:: org.codehaus.jackson JsonFactory

.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils PollingHttpClient

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

AdminBundleIT
=============

.. java:package:: org.motechproject.admin.osgi
   :noindex:

.. java:type:: public class AdminBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: AdminBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: AdminBundleIT

onTearDown
^^^^^^^^^^

.. java:method:: @Override protected void onTearDown() throws Exception
   :outertype: AdminBundleIT

testAdminBundleContext
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testAdminBundleContext()
   :outertype: AdminBundleIT

testBundleController
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testBundleController() throws IOException, InterruptedException
   :outertype: AdminBundleIT

testMessageController
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testMessageController() throws IOException, InterruptedException
   :outertype: AdminBundleIT

testSettingsController
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testSettingsController() throws IOException, InterruptedException
   :outertype: AdminBundleIT

testStatusMessageService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testStatusMessageService()
   :outertype: AdminBundleIT

