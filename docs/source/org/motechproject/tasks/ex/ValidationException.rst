.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: java.util Set

ValidationException
===================

.. java:package:: org.motechproject.tasks.ex
   :noindex:

.. java:type:: public class ValidationException extends IllegalArgumentException

Constructors
------------
ValidationException
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ValidationException(String objectType, Set<TaskError> taskErrors)
   :outertype: ValidationException

Methods
-------
getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage()
   :outertype: ValidationException

getTaskErrors
^^^^^^^^^^^^^

.. java:method:: public Set<TaskError> getTaskErrors()
   :outertype: ValidationException

