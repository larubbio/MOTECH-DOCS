.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time Period

.. java:import:: org.motechproject.commons.date.util DateUtil

PeriodicAggregationRecord
=========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class PeriodicAggregationRecord extends AggregationScheduleRecord implements PeriodicAggregation

Constructors
------------
PeriodicAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicAggregationRecord()
   :outertype: PeriodicAggregationRecord

PeriodicAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicAggregationRecord(Period period, DateTime startDate)
   :outertype: PeriodicAggregationRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: PeriodicAggregationRecord

getPeriod
^^^^^^^^^

.. java:method:: @Override public Period getPeriod()
   :outertype: PeriodicAggregationRecord

getStartTime
^^^^^^^^^^^^

.. java:method:: @Override @JsonProperty public DateTime getStartTime()
   :outertype: PeriodicAggregationRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: PeriodicAggregationRecord

setPeriod
^^^^^^^^^

.. java:method:: public void setPeriod(Period period)
   :outertype: PeriodicAggregationRecord

setStartDate
^^^^^^^^^^^^

.. java:method:: public void setStartDate(DateTime startDate)
   :outertype: PeriodicAggregationRecord

