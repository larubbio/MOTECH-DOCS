.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.event SporadicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

SporadicDispatcherTest
======================

.. java:package:: org.motechproject.event.aggregation.dispatch
   :noindex:

.. java:type:: public class SporadicDispatcherTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: SporadicDispatcherTest

shouldPublishAggregatedEventIfRuleIsNotSatisfied
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPublishAggregatedEventIfRuleIsNotSatisfied()
   :outertype: SporadicDispatcherTest

shouldPublishAggregatedEventWhenRuleIsSatisfied
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPublishAggregatedEventWhenRuleIsSatisfied()
   :outertype: SporadicDispatcherTest

