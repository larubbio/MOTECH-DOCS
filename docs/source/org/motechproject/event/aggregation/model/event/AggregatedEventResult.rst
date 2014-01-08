.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.joda.time DateTime

.. java:import:: java.io Serializable

.. java:import:: java.util Map

AggregatedEventResult
=====================

.. java:package:: org.motechproject.event.aggregation.model.event
   :noindex:

.. java:type:: public class AggregatedEventResult implements AggregatedEvent, Serializable

Constructors
------------
AggregatedEventResult
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregatedEventResult(Map<String, Object> aggregationParams, Map<String, Object> nonAggregationParams, DateTime timeStamp)
   :outertype: AggregatedEventResult

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: AggregatedEventResult

getAggregationParams
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Map<String, Object> getAggregationParams()
   :outertype: AggregatedEventResult

getNonAggregationParams
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Map<String, Object> getNonAggregationParams()
   :outertype: AggregatedEventResult

getTimeStamp
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public DateTime getTimeStamp()
   :outertype: AggregatedEventResult

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AggregatedEventResult

