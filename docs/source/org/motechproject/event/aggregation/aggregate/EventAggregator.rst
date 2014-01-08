.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util TreeMap

EventAggregator
===============

.. java:package:: org.motechproject.event.aggregation.aggregate
   :noindex:

.. java:type:: public class EventAggregator implements EventListener

Constructors
------------
EventAggregator
^^^^^^^^^^^^^^^

.. java:constructor:: public EventAggregator(String aggregationRuleName, List<String> fields, AllAggregatedEvents allAggregatedEvents, AllAggregationRules allAggregationRules)
   :outertype: EventAggregator

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: EventAggregator

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: EventAggregator

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: EventAggregator

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: EventAggregator

