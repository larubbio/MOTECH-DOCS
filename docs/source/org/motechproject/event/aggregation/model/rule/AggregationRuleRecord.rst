.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.event.aggregation.model.schedule AggregationScheduleRecord

.. java:import:: java.util List

AggregationRuleRecord
=====================

.. java:package:: org.motechproject.event.aggregation.model.rule
   :noindex:

.. java:type:: @TypeDiscriminator public class AggregationRuleRecord extends MotechBaseDataObject implements AggregationRule

Constructors
------------
AggregationRuleRecord
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregationRuleRecord()
   :outertype: AggregationRuleRecord

AggregationRuleRecord
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregationRuleRecord(String name, String description, String subscribedTo, List<String> fields, AggregationScheduleRecord schedule, String publishAs, AggregationState state)
   :outertype: AggregationRuleRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: AggregationRuleRecord

getAggregationSchedule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public AggregationScheduleRecord getAggregationSchedule()
   :outertype: AggregationRuleRecord

getDescription
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getDescription()
   :outertype: AggregationRuleRecord

getFields
^^^^^^^^^

.. java:method:: @JsonIgnore @Override public List<String> getFields()
   :outertype: AggregationRuleRecord

getName
^^^^^^^

.. java:method:: @JsonIgnore @Override public String getName()
   :outertype: AggregationRuleRecord

getPublishAs
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getPublishAs()
   :outertype: AggregationRuleRecord

getState
^^^^^^^^

.. java:method:: @JsonIgnore @Override public AggregationState getState()
   :outertype: AggregationRuleRecord

getSubscribedTo
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getSubscribedTo()
   :outertype: AggregationRuleRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AggregationRuleRecord

setAggregationSchedule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setAggregationSchedule(AggregationScheduleRecord aggregationSchedule)
   :outertype: AggregationRuleRecord

setDescription
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setDescription(String description)
   :outertype: AggregationRuleRecord

setFields
^^^^^^^^^

.. java:method:: @JsonIgnore public void setFields(List<String> fields)
   :outertype: AggregationRuleRecord

setName
^^^^^^^

.. java:method:: @JsonIgnore public void setName(String name)
   :outertype: AggregationRuleRecord

setPublishAs
^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setPublishAs(String publishAs)
   :outertype: AggregationRuleRecord

setState
^^^^^^^^

.. java:method:: @JsonIgnore public void setState(AggregationState state)
   :outertype: AggregationRuleRecord

setSubscribedTo
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setSubscribedTo(String subscribedTo)
   :outertype: AggregationRuleRecord

