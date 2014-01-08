.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain FieldParameter

.. java:import:: org.motechproject.tasks.domain Parameter

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.osgi.framework Version

.. java:import:: java.util Collection

.. java:import:: java.util HashSet

.. java:import:: java.util Set

GeneralValidator
================

.. java:package:: org.motechproject.tasks.validation
   :noindex:

.. java:type:: public abstract class GeneralValidator

Methods
-------
checkBlankValue
^^^^^^^^^^^^^^^

.. java:method:: protected static void checkBlankValue(Set<TaskError> errors, String objectName, String field, String value)
   :outertype: GeneralValidator

checkEmpty
^^^^^^^^^^

.. java:method:: protected static boolean checkEmpty(Set<TaskError> errors, String objectName, String field, Collection<?> collection)
   :outertype: GeneralValidator

checkNullValue
^^^^^^^^^^^^^^

.. java:method:: protected static void checkNullValue(Set<TaskError> errors, String objectName, String field, Object value)
   :outertype: GeneralValidator

checkVersion
^^^^^^^^^^^^

.. java:method:: protected static void checkVersion(Set<TaskError> errors, String objectName, String field, String value)
   :outertype: GeneralValidator

validateActionParameter
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected static Set<TaskError> validateActionParameter(String objectName, String field, ActionParameter parameter)
   :outertype: GeneralValidator

validateEventParameter
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected static Set<TaskError> validateEventParameter(String objectName, String field, EventParameter parameter)
   :outertype: GeneralValidator

validateFieldParameter
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected static Set<TaskError> validateFieldParameter(String objectName, String field, FieldParameter parameter)
   :outertype: GeneralValidator

