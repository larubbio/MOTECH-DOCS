.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util List

RequiredFieldValidator
======================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class RequiredFieldValidator implements AbstractValidator

   Generic validator class that validates presence of a given field

Fields
------
ERROR_REQUIRED
^^^^^^^^^^^^^^

.. java:field:: public static final String ERROR_REQUIRED
   :outertype: RequiredFieldValidator

Constructors
------------
RequiredFieldValidator
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public RequiredFieldValidator(String fieldName, String fieldValue)
   :outertype: RequiredFieldValidator

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: RequiredFieldValidator

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: RequiredFieldValidator

validate
^^^^^^^^

.. java:method:: @Override public void validate(StartupForm target, List<String> errors)
   :outertype: RequiredFieldValidator

