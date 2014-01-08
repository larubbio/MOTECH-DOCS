.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.motechproject.event.aggregation.model.schedule AggregationScheduleRequest

.. java:import:: javax.validation Valid

.. java:import:: javax.validation.constraints NotNull

.. java:import:: javax.validation.constraints Size

.. java:import:: java.util List

AggregationRuleRequest
======================

.. java:package:: org.motechproject.event.aggregation.model.rule
   :noindex:

.. java:type:: public class AggregationRuleRequest implements AggregationRule

Constructors
------------
AggregationRuleRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregationRuleRequest()
   :outertype: AggregationRuleRequest

AggregationRuleRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregationRuleRequest(String name, String description, String subscribedTo, List<String> fields, AggregationScheduleRequest aggregationSchedule, String publishAs, AggregationState state)
   :outertype: AggregationRuleRequest

Methods
-------
getAggregationSchedule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public AggregationScheduleRequest getAggregationSchedule()
   :outertype: AggregationRuleRequest

getDescription
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getDescription()
   :outertype: AggregationRuleRequest

getFields
^^^^^^^^^

.. java:method:: @JsonIgnore @Override public List<String> getFields()
   :outertype: AggregationRuleRequest

getName
^^^^^^^

.. java:method:: @JsonIgnore @Override public String getName()
   :outertype: AggregationRuleRequest

getPublishAs
^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getPublishAs()
   :outertype: AggregationRuleRequest

getState
^^^^^^^^

.. java:method:: @Override @JsonIgnore public AggregationState getState()
   :outertype: AggregationRuleRequest

getSubscribedTo
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore @Override public String getSubscribedTo()
   :outertype: AggregationRuleRequest

setAggregationSchedule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setAggregationSchedule(AggregationScheduleRequest aggregationSchedule)
   :outertype: AggregationRuleRequest

setDescription
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setDescription(String description)
   :outertype: AggregationRuleRequest

setFields
^^^^^^^^^

.. java:method:: @JsonIgnore public void setFields(List<String> fields)
   :outertype: AggregationRuleRequest

setName
^^^^^^^

.. java:method:: @JsonIgnore public void setName(String name)
   :outertype: AggregationRuleRequest

setPublishAs
^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setPublishAs(String publishAs)
   :outertype: AggregationRuleRequest

setState
^^^^^^^^

.. java:method:: @JsonIgnore public void setState(AggregationState state)
   :outertype: AggregationRuleRequest

setSubscribedTo
^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setSubscribedTo(String subscribedTo)
   :outertype: AggregationRuleRequest

