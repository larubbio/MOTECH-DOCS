.. java:import:: org.motechproject.event.aggregation.model.schedule AggregationScheduleRecord

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRecord

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRecord

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRecord

.. java:import:: org.motechproject.event.aggregation.model.schedule AggregationScheduleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

AggregationScheduleMapper
=========================

.. java:package:: org.motechproject.event.aggregation.model.mapper
   :noindex:

.. java:type:: public class AggregationScheduleMapper

Methods
-------
toRecord
^^^^^^^^

.. java:method:: public AggregationScheduleRecord toRecord(AggregationScheduleRequest request)
   :outertype: AggregationScheduleMapper

toRequest
^^^^^^^^^

.. java:method:: public AggregationScheduleRequest toRequest(AggregationScheduleRecord record)
   :outertype: AggregationScheduleMapper

