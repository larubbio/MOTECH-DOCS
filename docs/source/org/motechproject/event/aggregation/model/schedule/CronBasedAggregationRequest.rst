.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.motechproject.event.aggregation.model.validate ValidCron

.. java:import:: javax.validation.constraints NotNull

.. java:import:: javax.validation.constraints Size

CronBasedAggregationRequest
===========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class CronBasedAggregationRequest extends AggregationScheduleRequest implements CronBasedAggregation

Constructors
------------
CronBasedAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronBasedAggregationRequest()
   :outertype: CronBasedAggregationRequest

CronBasedAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronBasedAggregationRequest(String cronExpression)
   :outertype: CronBasedAggregationRequest

Methods
-------
getCronExpression
^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getCronExpression()
   :outertype: CronBasedAggregationRequest

setCronExpression
^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setCronExpression(String cronExpression)
   :outertype: CronBasedAggregationRequest

