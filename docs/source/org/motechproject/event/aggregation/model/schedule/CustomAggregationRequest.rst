.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.motechproject.event.aggregation.model.validate ValidRuleExpression

.. java:import:: javax.validation.constraints NotNull

.. java:import:: javax.validation.constraints Size

CustomAggregationRequest
========================

.. java:package:: org.motechproject.event.aggregation.model.schedule
   :noindex:

.. java:type:: public class CustomAggregationRequest extends AggregationScheduleRequest implements CustomAggregation

Constructors
------------
CustomAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CustomAggregationRequest()
   :outertype: CustomAggregationRequest

CustomAggregationRequest
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CustomAggregationRequest(String rule)
   :outertype: CustomAggregationRequest

Methods
-------
getRule
^^^^^^^

.. java:method:: @JsonIgnore @Override public String getRule()
   :outertype: CustomAggregationRequest

setRule
^^^^^^^

.. java:method:: @JsonIgnore public void setRule(String rule)
   :outertype: CustomAggregationRequest

