.. java:import:: org.apache.commons.httpclient HttpStatus

.. java:import:: org.apache.http Header

.. java:import:: org.apache.http HttpHeaders

.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http NameValuePair

.. java:import:: org.apache.http.client.entity UrlEncodedFormEntity

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.impl.client BasicCookieStore

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.apache.http.message BasicNameValuePair

.. java:import:: org.apache.http.util EntityUtils

.. java:import:: org.hamcrest.core Is

.. java:import:: org.json JSONException

.. java:import:: org.junit Test

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

RestAPIAuthenticationIT
=======================

.. java:package:: org.motechproject.server
   :noindex:

.. java:type:: public class RestAPIAuthenticationIT

Methods
-------
testThatItShouldAllowRestApiAccessAfterFormAuthentication
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testThatItShouldAllowRestApiAccessAfterFormAuthentication() throws IOException, JSONException, InterruptedException
   :outertype: RestAPIAuthenticationIT

