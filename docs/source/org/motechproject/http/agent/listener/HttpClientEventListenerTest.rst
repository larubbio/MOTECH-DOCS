.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.mockito.runners MockitoJUnitRunner

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.http.agent.domain EventDataKeys

.. java:import:: org.motechproject.http.agent.domain EventSubjects

.. java:import:: org.motechproject.http.agent.domain Method

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.http.client HttpComponentsClientHttpRequestFactory

.. java:import:: org.springframework.web.client RestTemplate

.. java:import:: java.io IOException

.. java:import:: java.util HashMap

HttpClientEventListenerTest
===========================

.. java:package:: org.motechproject.http.agent.listener
   :noindex:

.. java:type:: @RunWith public class HttpClientEventListenerTest

Fields
------
httpComponentsClientHttpRequestFactory
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  HttpComponentsClientHttpRequestFactory httpComponentsClientHttpRequestFactory
   :outertype: HttpClientEventListenerTest

settings
^^^^^^^^

.. java:field:: @Mock  SettingsFacade settings
   :outertype: HttpClientEventListenerTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: HttpClientEventListenerTest

shouldReadFromQueueAndMakeAHttpCall
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReadFromQueueAndMakeAHttpCall() throws IOException
   :outertype: HttpClientEventListenerTest

shouldReadFromQueueAndMakeAHttpCallForPost
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReadFromQueueAndMakeAHttpCallForPost() throws IOException
   :outertype: HttpClientEventListenerTest

shouldReadFromQueueAndMakeAHttpDeleteCall
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReadFromQueueAndMakeAHttpDeleteCall() throws IOException
   :outertype: HttpClientEventListenerTest

