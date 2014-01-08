.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.event.aggregation.aggregate EventAggregator

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.event PeriodicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.model.event SporadicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRule

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule AggregationScheduleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRequest

.. java:import:: org.motechproject.event.aggregation.service EventAggregationService

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

EventAggregationServiceImpl
===========================

.. java:package:: org.motechproject.event.aggregation.service.impl
   :noindex:

.. java:type:: @Service public class EventAggregationServiceImpl implements EventAggregationService

Fields
------
MILLIS_IN_A_SEC
^^^^^^^^^^^^^^^

.. java:field:: public static final int MILLIS_IN_A_SEC
   :outertype: EventAggregationServiceImpl

Constructors
------------
EventAggregationServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public EventAggregationServiceImpl(AllAggregationRules allAggregationRules, EventListenerRegistryService eventListenerRegistryService, AllAggregatedEvents allAggregatedEvents, MotechSchedulerService schedulerService)
   :outertype: EventAggregationServiceImpl

Methods
-------
createRule
^^^^^^^^^^

.. java:method:: @Override public void createRule(AggregationRuleRequest request)
   :outertype: EventAggregationServiceImpl

