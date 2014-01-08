.. java:import:: org.motechproject.metrics MetricsAgentBackend

.. java:import:: org.motechproject.metrics.domain ConfigProperty

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.net InetAddress

.. java:import:: java.net UnknownHostException

.. java:import:: java.util HashMap

.. java:import:: java.util Map

LoggingAgentBackendImpl
=======================

.. java:package:: org.motechproject.metrics.impl
   :noindex:

.. java:type:: public class LoggingAgentBackendImpl implements MetricsAgentBackend

   A very simple metric backend that logs all metrics in a format splunk can parse (i.e key=value)

Constructors
------------
LoggingAgentBackendImpl
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public LoggingAgentBackendImpl()
   :outertype: LoggingAgentBackendImpl

Methods
-------
getImplementationName
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public String getImplementationName()
   :outertype: LoggingAgentBackendImpl

getSettings
^^^^^^^^^^^

.. java:method:: @Override public Map<String, ConfigProperty> getSettings()
   :outertype: LoggingAgentBackendImpl

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric, Map<String, String> parameters)
   :outertype: LoggingAgentBackendImpl

   Reports an occurrence of metric, incrementing it's count. Not all implementations may make use of parameters

   :param metric: The metric being recorded
   :param parameters: Optional parameters related to the event

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric)
   :outertype: LoggingAgentBackendImpl

   Reports an occurrence of metric, incrementing it's count.

   :param metric: The metric being recorded

logTimedEvent
^^^^^^^^^^^^^

.. java:method:: @Override public void logTimedEvent(String metric, long time)
   :outertype: LoggingAgentBackendImpl

   Reports an occurance of metric in milliseconds

   :param metric: The metric being recorded
   :param time: The execution time of this event in milliseconds

saveSettings
^^^^^^^^^^^^

.. java:method:: @Override public void saveSettings(Map<String, ConfigProperty> config)
   :outertype: LoggingAgentBackendImpl

