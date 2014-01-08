.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.rule RuleAgent

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEvent

.. java:import:: javax.validation ConstraintValidator

.. java:import:: javax.validation ConstraintValidatorContext

.. java:import:: java.util HashMap

.. java:import:: java.util List

RuleExpressionValidator
=======================

.. java:package:: org.motechproject.event.aggregation.model.validate
   :noindex:

.. java:type:: public class RuleExpressionValidator implements ConstraintValidator<ValidRuleExpression, String>

Methods
-------
initialize
^^^^^^^^^^

.. java:method:: @Override public void initialize(ValidRuleExpression validRuleExpression)
   :outertype: RuleExpressionValidator

isValid
^^^^^^^

.. java:method:: @Override public boolean isValid(String expression, ConstraintValidatorContext constraintValidatorContext)
   :outertype: RuleExpressionValidator

