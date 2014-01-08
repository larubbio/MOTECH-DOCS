.. java:import:: org.motechproject.commons.date ParseException

.. java:import:: org.motechproject.commons.date.util JodaFormatter

.. java:import:: javax.validation ConstraintValidator

.. java:import:: javax.validation ConstraintValidatorContext

PeriodValidator
===============

.. java:package:: org.motechproject.event.aggregation.model.validate
   :noindex:

.. java:type:: public class PeriodValidator implements ConstraintValidator<ValidPeriod, String>

Methods
-------
initialize
^^^^^^^^^^

.. java:method:: @Override public void initialize(ValidPeriod validPeriod)
   :outertype: PeriodValidator

isValid
^^^^^^^

.. java:method:: @Override public boolean isValid(String periodString, ConstraintValidatorContext constraintValidatorContext)
   :outertype: PeriodValidator

