.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http HttpStatus

.. java:import:: org.apache.http.client CredentialsProvider

.. java:import:: org.apache.http.client ResponseHandler

.. java:import:: org.apache.http.client.methods HttpGet

.. java:import:: org.apache.http.client.methods HttpUriRequest

.. java:import:: org.apache.http.impl.client DefaultHttpClient

.. java:import:: org.apache.http.util EntityUtils

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io IOException

PollingHttpClient
=================

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: public class PollingHttpClient

Constructors
------------
PollingHttpClient
^^^^^^^^^^^^^^^^^

.. java:constructor:: public PollingHttpClient()
   :outertype: PollingHttpClient

PollingHttpClient
^^^^^^^^^^^^^^^^^

.. java:constructor:: public PollingHttpClient(DefaultHttpClient httpClient, int waitPeriodInSeconds)
   :outertype: PollingHttpClient

Methods
-------
execute
^^^^^^^

.. java:method:: public HttpResponse execute(HttpUriRequest request) throws IOException, InterruptedException
   :outertype: PollingHttpClient

execute
^^^^^^^

.. java:method:: public <T> T execute(HttpUriRequest request, ResponseHandler<? extends T> responseHandler) throws IOException, InterruptedException
   :outertype: PollingHttpClient

get
^^^

.. java:method:: public HttpResponse get(String uri) throws IOException, InterruptedException
   :outertype: PollingHttpClient

get
^^^

.. java:method:: public <T> T get(String uri, ResponseHandler<? extends T> responseHandler) throws IOException, InterruptedException
   :outertype: PollingHttpClient

getCredentialsProvider
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public CredentialsProvider getCredentialsProvider()
   :outertype: PollingHttpClient

