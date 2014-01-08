.. java:import:: org.joda.time Period

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event.aggregation.aggregate EventAggregator

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.event PeriodicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.model.event SporadicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRecord

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRecord

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRequest

.. java:import:: org.motechproject.event.aggregation.service EventAggregationService

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: java.util ArrayList

.. java:import:: java.util List

EventAggregationServiceImplTest
===============================

.. java:package:: org.motechproject.event.aggregation.service.impl
   :noindex:

.. java:type:: public class EventAggregationServiceImplTest

Fields
------
eventAggregationService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  EventAggregationService eventAggregationService
   :outertype: EventAggregationServiceImplTest

eventListenerRegistryService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  EventListenerRegistryService eventListenerRegistryService
   :outertype: EventAggregationServiceImplTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: EventAggregationServiceImplTest

shouldCreateAggregationRule
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateAggregationRule()
   :outertype: EventAggregationServiceImplTest

shouldScheduleCronJobToDispatchCronBasedAggregation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleCronJobToDispatchCronBasedAggregation()
   :outertype: EventAggregationServiceImplTest

shouldScheduleMinutelyJobToDispatchAggregationsInARollingWindow
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleMinutelyJobToDispatchAggregationsInARollingWindow()
   :outertype: EventAggregationServiceImplTest

shouldScheduleRepeatJobToDispatchPeriodicAggregation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleRepeatJobToDispatchPeriodicAggregation()
   :outertype: EventAggregationServiceImplTest

shouldSubscribeToAggregatedEventsOnStartup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSubscribeToAggregatedEventsOnStartup()
   :outertype: EventAggregationServiceImplTest

shouldSubscribeToAggregationEventsForAllRulesOnStartup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSubscribeToAggregationEventsForAllRulesOnStartup()
   :outertype: EventAggregationServiceImplTest

