.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.event.metrics MetricsAgent

.. java:import:: org.motechproject.metrics MetricsAgentBackend

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Map

MultipleMetricsAgentImpl
========================

.. java:package:: org.motechproject.metrics.impl
   :noindex:

.. java:type:: @Service public class MultipleMetricsAgentImpl implements MetricsAgent

   Implementation of {@Link MetricsAgent} interface

Constructors
------------
MultipleMetricsAgentImpl
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MultipleMetricsAgentImpl()
   :outertype: MultipleMetricsAgentImpl

Methods
-------
addMetricAgent
^^^^^^^^^^^^^^

.. java:method:: public void addMetricAgent(MetricsAgentBackend agent)
   :outertype: MultipleMetricsAgentImpl

getMetricsAgents
^^^^^^^^^^^^^^^^

.. java:method:: public List<MetricsAgentBackend> getMetricsAgents()
   :outertype: MultipleMetricsAgentImpl

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric, Map<String, String> parameters)
   :outertype: MultipleMetricsAgentImpl

   Reports an occurrence of metric, incrementing it's count. Not all implementations may make use of parameters

   :param metric: The metric being recorded
   :param parameters: Optional parameters related to the event

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric)
   :outertype: MultipleMetricsAgentImpl

   Reports an occurrence of metric, incrementing it's count.

   :param metric: The metric being recorded

removeMetricAgent
^^^^^^^^^^^^^^^^^

.. java:method:: public void removeMetricAgent(MetricsAgentBackend agent)
   :outertype: MultipleMetricsAgentImpl

setMetricsAgents
^^^^^^^^^^^^^^^^

.. java:method:: public void setMetricsAgents(List<MetricsAgentBackend> agents)
   :outertype: MultipleMetricsAgentImpl

startTimer
^^^^^^^^^^

.. java:method:: @Override public long startTimer()
   :outertype: MultipleMetricsAgentImpl

   Starts a timer for metric. Later calls to startTimer without a corresponding call to endTimer for the same metric are ignored

stopTimer
^^^^^^^^^

.. java:method:: @Override public void stopTimer(String metric, Long startTime)
   :outertype: MultipleMetricsAgentImpl

   Ends the timer for metric and records it. No action is taken if a start timer was not recorded for metric

   :param metric: The metric being timed
   :param startTime:

