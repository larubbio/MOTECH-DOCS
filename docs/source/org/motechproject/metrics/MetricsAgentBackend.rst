.. java:import:: org.motechproject.metrics.domain ConfigProperty

.. java:import:: java.util Map

MetricsAgentBackend
===================

.. java:package:: org.motechproject.metrics
   :noindex:

.. java:type:: public interface MetricsAgentBackend

   A simple interface for metrics allowing event logging

Methods
-------
getImplementationName
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  String getImplementationName()
   :outertype: MetricsAgentBackend

getSettings
^^^^^^^^^^^

.. java:method::  Map<String, ConfigProperty> getSettings()
   :outertype: MetricsAgentBackend

   Should return config properties of current implementation. If there are no settings, then method should return empty map

logEvent
^^^^^^^^

.. java:method::  void logEvent(String metric, Map<String, String> parameters)
   :outertype: MetricsAgentBackend

   Reports an occurrence of metric, incrementing it's count. Not all implementations may make use of parameters

   :param metric: The metric being recorded
   :param parameters: Optional parameters related to the event

logEvent
^^^^^^^^

.. java:method::  void logEvent(String metric)
   :outertype: MetricsAgentBackend

   Reports an occurrence of metric, incrementing it's count.

   :param metric: The metric being recorded

logTimedEvent
^^^^^^^^^^^^^

.. java:method::  void logTimedEvent(String metric, long time)
   :outertype: MetricsAgentBackend

   Reports an occurance of metric in milliseconds

   :param metric: The metric being recorded
   :param time: The execution time of this event in milliseconds

saveSettings
^^^^^^^^^^^^

.. java:method::  void saveSettings(Map<String, ConfigProperty> config)
   :outertype: MetricsAgentBackend

   Should save new config

