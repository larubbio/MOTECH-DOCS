.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventResult

.. java:import:: java.util ArrayList

.. java:import:: java.util List

Aggregation
===========

.. java:package:: org.motechproject.event.aggregation.model
   :noindex:

.. java:type:: public class Aggregation

Constructors
------------
Aggregation
^^^^^^^^^^^

.. java:constructor:: public Aggregation(String aggregationRuleName, List<AggregatedEventRecord> eventRecords)
   :outertype: Aggregation

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: Aggregation

getAggregationRuleName
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getAggregationRuleName()
   :outertype: Aggregation

getEventRecords
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public List<AggregatedEventRecord> getEventRecords()
   :outertype: Aggregation

getEvents
^^^^^^^^^

.. java:method:: @JsonIgnore public List<AggregatedEventResult> getEvents()
   :outertype: Aggregation

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Aggregation

