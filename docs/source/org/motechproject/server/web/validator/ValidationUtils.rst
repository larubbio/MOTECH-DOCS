.. java:import:: org.apache.commons.validator UrlValidator

.. java:import:: org.springframework.validation Errors

ValidationUtils
===============

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public final class ValidationUtils

   Validation utils that consists of common validations that can be used across multiple controllers.

Methods
-------
validateEmptyOrWhitespace
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static void validateEmptyOrWhitespace(Errors errors, String errorMessageFormat, String... fields)
   :outertype: ValidationUtils

validateUrl
^^^^^^^^^^^

.. java:method:: public static void validateUrl(Errors errors, String dbUrlField)
   :outertype: ValidationUtils

