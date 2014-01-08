.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.eventlogging.domain CouchLogMappings

.. java:import:: org.motechproject.eventlogging.domain CouchLoggableEvent

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.motechproject.eventlogging.domain MappingsJson

.. java:import:: org.motechproject.eventlogging.domain ParametersPresentEventFlag

.. java:import:: org.motechproject.eventlogging.loggers.impl CouchEventLogger

.. java:import:: org.motechproject.eventlogging.repository AllEventMappings

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

CouchEventLoggingServiceTest
============================

.. java:package:: org.motechproject.eventlogging.service.impl
   :noindex:

.. java:type:: public class CouchEventLoggingServiceTest

Fields
------
allEventMappings
^^^^^^^^^^^^^^^^

.. java:field:: @Mock  AllEventMappings allEventMappings
   :outertype: CouchEventLoggingServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: CouchEventLoggingServiceTest

shouldSetAllLoggableEventsCorrectly
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSetAllLoggableEventsCorrectly()
   :outertype: CouchEventLoggingServiceTest

