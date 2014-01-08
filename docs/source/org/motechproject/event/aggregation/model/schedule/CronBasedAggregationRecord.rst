.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

CronBasedAggregationRecord
==========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class CronBasedAggregationRecord extends AggregationScheduleRecord implements CronBasedAggregation

Constructors
------------
CronBasedAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronBasedAggregationRecord()
   :outertype: CronBasedAggregationRecord

CronBasedAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronBasedAggregationRecord(CronBasedAggregationRequest request)
   :outertype: CronBasedAggregationRecord

CronBasedAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronBasedAggregationRecord(String cronExpression)
   :outertype: CronBasedAggregationRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: CronBasedAggregationRecord

getCronExpression
^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getCronExpression()
   :outertype: CronBasedAggregationRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: CronBasedAggregationRecord

setCronExpression
^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setCronExpression(String cronExpression)
   :outertype: CronBasedAggregationRecord

