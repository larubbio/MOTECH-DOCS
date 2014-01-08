.. java:import:: java.util Map

MetricsAgent
============

.. java:package:: org.motechproject.event.metrics
   :noindex:

.. java:type:: public interface MetricsAgent

   Interface into the metrics system

Methods
-------
logEvent
^^^^^^^^

.. java:method::  void logEvent(String metric, Map<String, String> parameters)
   :outertype: MetricsAgent

   Reports an occurrence of metric, incrementing it's count. Not all implementations may make use of parameters

   :param metric: The metric being recorded
   :param parameters: Optional parameters related to the event

logEvent
^^^^^^^^

.. java:method::  void logEvent(String metric)
   :outertype: MetricsAgent

   Reports an occurrence of metric, incrementing it's count.

   :param metric: The metric being recorded

startTimer
^^^^^^^^^^

.. java:method::  long startTimer()
   :outertype: MetricsAgent

   Starts a timer for metric. Later calls to startTimer without a corresponding call to endTimer for the same metric are ignored

stopTimer
^^^^^^^^^

.. java:method::  void stopTimer(String metric, Long timerValue)
   :outertype: MetricsAgent

   Ends the timer for metric and records it. No action is taken if a start timer was not recorded for metric

   :param metric: The metric being timed
   :param timerValue:

