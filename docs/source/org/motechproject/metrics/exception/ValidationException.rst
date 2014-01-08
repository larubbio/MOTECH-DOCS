.. java:import:: java.util Map

ValidationException
===================

.. java:package:: org.motechproject.metrics.exception
   :noindex:

.. java:type:: public class ValidationException extends IllegalArgumentException

   Exception thrown by metric agent backend implementation when config saving fails

Constructors
------------
ValidationException
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ValidationException(String implementationName, Map<String, String> errors)
   :outertype: ValidationException

Methods
-------
getErrors
^^^^^^^^^

.. java:method:: public Map<String, String> getErrors()
   :outertype: ValidationException

getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage()
   :outertype: ValidationException

