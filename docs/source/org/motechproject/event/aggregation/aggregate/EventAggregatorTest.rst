.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRecord

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util Map

EventAggregatorTest
===================

.. java:package:: org.motechproject.event.aggregation.aggregate
   :noindex:

.. java:type:: public class EventAggregatorTest

Fields
------
eventAggregator
^^^^^^^^^^^^^^^

.. java:field::  EventAggregator eventAggregator
   :outertype: EventAggregatorTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: EventAggregatorTest

shouldAddEventToAggregation
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddEventToAggregation()
   :outertype: EventAggregatorTest

shouldMarkAggregateEventIfItHasAnyFieldMissing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldMarkAggregateEventIfItHasAnyFieldMissing()
   :outertype: EventAggregatorTest

shouldNotAggregateWhilePaused
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAggregateWhilePaused()
   :outertype: EventAggregatorTest

shouldSortKeysInAggregatedParametersMap
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSortKeysInAggregatedParametersMap()
   :outertype: EventAggregatorTest

