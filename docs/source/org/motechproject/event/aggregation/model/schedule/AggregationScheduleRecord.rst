.. java:import:: org.codehaus.jackson.annotate JsonSubTypes

.. java:import:: org.codehaus.jackson.annotate JsonTypeInfo

.. java:import:: java.io Serializable

AggregationScheduleRecord
=========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: @JsonTypeInfo @JsonSubTypes public abstract class AggregationScheduleRecord implements AggregationSchedule, Serializable

Constructors
------------
AggregationScheduleRecord
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: protected AggregationScheduleRecord()
   :outertype: AggregationScheduleRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: AggregationScheduleRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AggregationScheduleRecord

