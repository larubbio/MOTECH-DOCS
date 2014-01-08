.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model AggregationEvent

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util List

EventDispatcher
===============

.. java:package:: org.motechproject.event.aggregation.dispatch
   :noindex:

.. java:type:: @Component public class EventDispatcher

Constructors
------------
EventDispatcher
^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public EventDispatcher(AllAggregatedEvents allAggregatedEvents, EventRelay eventRelay, AllAggregationRules allAggregationRules)
   :outertype: EventDispatcher

Methods
-------
dispatch
^^^^^^^^

.. java:method:: public void dispatch(String aggregationRuleName)
   :outertype: EventDispatcher

