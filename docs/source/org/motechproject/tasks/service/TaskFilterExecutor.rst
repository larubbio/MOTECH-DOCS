.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time Days

.. java:import:: org.joda.time Months

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain KeyInformation

.. java:import:: org.motechproject.tasks.domain OperatorType

.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: org.motechproject.tasks.events.constants TaskFailureCause

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.math BigDecimal

.. java:import:: java.util List

.. java:import:: java.util Map

TaskFilterExecutor
==================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public class TaskFilterExecutor

   The \ ``TaskFilterExecutor``\  applies a list of filters in a #\ :java:ref:`TaskContext`\ .

   ..

   * \ **convertTo**\  - convert a given value to a correct type,
   * \ **getFieldValue**\  - get value of a field defined in the key from the given object,
   * \ **getTriggerKey**\  - get value of a trigger event parameter,
   * \ **checkFilters**\  - executed defined filters for a task,
   * \ **manipulate**\  - executed the given manipulation on the given string value.

Methods
-------
checkFilters
^^^^^^^^^^^^

.. java:method:: public boolean checkFilters(List<Filter> filters, TaskContext taskContext) throws TaskHandlerException
   :outertype: TaskFilterExecutor

