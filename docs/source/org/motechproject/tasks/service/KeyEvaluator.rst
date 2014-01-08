.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.commons.lang WordUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.joda.time.format DateTimeFormatter

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.tasks.domain KeyInformation

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.util List

KeyEvaluator
============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public class KeyEvaluator

   KeyEvaluator evaluates the value of a key in the context of a task which is used to execute filters and actions.

Constructors
------------
KeyEvaluator
^^^^^^^^^^^^

.. java:constructor:: public KeyEvaluator(TaskContext taskContext)
   :outertype: KeyEvaluator

Methods
-------
evaluateTemplateString
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String evaluateTemplateString(String template) throws TaskHandlerException
   :outertype: KeyEvaluator

getValue
^^^^^^^^

.. java:method:: public Object getValue(KeyInformation keyInformation) throws TaskHandlerException
   :outertype: KeyEvaluator

manipulate
^^^^^^^^^^

.. java:method::  String manipulate(String manipulation, String value)
   :outertype: KeyEvaluator

