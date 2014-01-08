.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: java.util Map

AggregatedEventRecord
=====================

.. java:package:: org.motechproject.event.aggregation.model.event
   :noindex:

.. java:type:: @TypeDiscriminator public class AggregatedEventRecord extends MotechBaseDataObject implements AggregatedEvent

Constructors
------------
AggregatedEventRecord
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregatedEventRecord(String aggregationRuleName, Map<String, Object> aggregationParams, Map<String, Object> nonAggregationParams, boolean hasError)
   :outertype: AggregatedEventRecord

AggregatedEventRecord
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregatedEventRecord(String aggregationRuleName, Map<String, Object> aggregationParams, Map<String, Object> nonAggregationParams)
   :outertype: AggregatedEventRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: AggregatedEventRecord

getAggregationParams
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Map<String, Object> getAggregationParams()
   :outertype: AggregatedEventRecord

getAggregationRuleName
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getAggregationRuleName()
   :outertype: AggregatedEventRecord

getNonAggregationParams
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public Map<String, Object> getNonAggregationParams()
   :outertype: AggregatedEventRecord

getTimeStamp
^^^^^^^^^^^^

.. java:method:: @Override public DateTime getTimeStamp()
   :outertype: AggregatedEventRecord

hasError
^^^^^^^^

.. java:method:: @JsonIgnore public boolean hasError()
   :outertype: AggregatedEventRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AggregatedEventRecord

