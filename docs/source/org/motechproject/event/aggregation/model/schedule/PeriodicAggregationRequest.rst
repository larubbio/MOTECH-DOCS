.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time Period

.. java:import:: org.motechproject.commons.date.util JodaFormatter

.. java:import:: org.motechproject.event.aggregation.model.validate ValidPeriod

.. java:import:: javax.validation.constraints NotNull

.. java:import:: javax.validation.constraints Size

PeriodicAggregationRequest
==========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class PeriodicAggregationRequest extends AggregationScheduleRequest implements PeriodicAggregation

Constructors
------------
PeriodicAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicAggregationRequest()
   :outertype: PeriodicAggregationRequest

PeriodicAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicAggregationRequest(String period, DateTime startTime)
   :outertype: PeriodicAggregationRequest

Methods
-------
getPeriod
^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Period getPeriod()
   :outertype: PeriodicAggregationRequest

getStartTime
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public DateTime getStartTime()
   :outertype: PeriodicAggregationRequest

setPeriod
^^^^^^^^^

.. java:method:: @JsonIgnore public void setPeriod(Period period)
   :outertype: PeriodicAggregationRequest

setStartTimeInMillis
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setStartTimeInMillis(DateTime date)
   :outertype: PeriodicAggregationRequest

