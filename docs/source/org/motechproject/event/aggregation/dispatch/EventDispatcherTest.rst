.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model AggregationEvent

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRecord

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: java.util HashMap

.. java:import:: java.util Map

EventDispatcherTest
===================

.. java:package:: org.motechproject.event.aggregation.dispatch
   :noindex:

.. java:type:: public class EventDispatcherTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: EventDispatcherTest

shouldClearCurrentAggregationAfterPublishingEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldClearCurrentAggregationAfterPublishingEvent()
   :outertype: EventDispatcherTest

shouldExtractAggregationAndPublishAggregatedEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldExtractAggregationAndPublishAggregatedEvent()
   :outertype: EventDispatcherTest

