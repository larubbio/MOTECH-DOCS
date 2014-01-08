.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http NameValuePair

.. java:import:: org.apache.http.client.entity UrlEncodedFormEntity

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.impl.client BasicCookieStore

.. java:import:: org.apache.http.impl.client BasicResponseHandler

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.apache.http.message BasicNameValuePair

.. java:import:: org.apache.http.util EntityUtils

.. java:import:: org.json JSONArray

.. java:import:: org.json JSONException

.. java:import:: org.junit Test

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

StartupIT
=========

.. java:package:: org.motechproject.server
   :noindex:

.. java:type:: public class StartupIT

Methods
-------
shouldStartServerAndMakeAllBundlesActive
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldStartServerAndMakeAllBundlesActive() throws IOException, JSONException, InterruptedException
   :outertype: StartupIT

