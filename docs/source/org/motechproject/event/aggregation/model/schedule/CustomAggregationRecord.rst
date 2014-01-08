.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

CustomAggregationRecord
=======================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class CustomAggregationRecord extends AggregationScheduleRecord implements CustomAggregation

Constructors
------------
CustomAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CustomAggregationRecord()
   :outertype: CustomAggregationRecord

CustomAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CustomAggregationRecord(CustomAggregationRequest request)
   :outertype: CustomAggregationRecord

CustomAggregationRecord
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CustomAggregationRecord(String rule)
   :outertype: CustomAggregationRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: CustomAggregationRecord

getRule
^^^^^^^

.. java:method:: @JsonIgnore @Override public String getRule()
   :outertype: CustomAggregationRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: CustomAggregationRecord

setRule
^^^^^^^

.. java:method:: @JsonIgnore public void setRule(String rule)
   :outertype: CustomAggregationRecord

