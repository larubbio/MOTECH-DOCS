.. java:import:: org.quartz CronExpression

.. java:import:: javax.validation ConstraintValidator

.. java:import:: javax.validation ConstraintValidatorContext

CronValidator
=============

.. java:package:: org.motechproject.event.aggregation.model.validate
   :noindex:

.. java:type:: public class CronValidator implements ConstraintValidator<ValidCron, String>

Methods
-------
initialize
^^^^^^^^^^

.. java:method:: @Override public void initialize(ValidCron validCron)
   :outertype: CronValidator

isValid
^^^^^^^

.. java:method:: @Override public boolean isValid(String cronExpression, ConstraintValidatorContext constraintValidatorContext)
   :outertype: CronValidator

