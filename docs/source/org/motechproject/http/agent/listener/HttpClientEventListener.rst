.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.motechproject.http.agent.domain EventDataKeys

.. java:import:: org.motechproject.http.agent.domain EventSubjects

.. java:import:: org.motechproject.http.agent.domain Method

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.http.client HttpComponentsClientHttpRequestFactory

.. java:import:: org.springframework.stereotype Component

.. java:import:: org.springframework.web.client RestTemplate

.. java:import:: java.util Map

HttpClientEventListener
=======================

.. java:package:: org.motechproject.http.agent.listener
   :noindex:

.. java:type:: @Component public class HttpClientEventListener

Fields
------
HTTP_CONNECT_TIMEOUT
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String HTTP_CONNECT_TIMEOUT
   :outertype: HttpClientEventListener

HTTP_READ_TIMEOUT
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String HTTP_READ_TIMEOUT
   :outertype: HttpClientEventListener

Constructors
------------
HttpClientEventListener
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public HttpClientEventListener(RestTemplate restTemplate, SettingsFacade settings)
   :outertype: HttpClientEventListener

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent motechEvent)
   :outertype: HttpClientEventListener

