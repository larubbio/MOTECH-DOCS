.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain KeyInformation

.. java:import:: org.motechproject.tasks.domain OperatorType

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskConfig

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.domain ManipulationType

.. java:import:: org.motechproject.tasks.domain ManipulationTarget

.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

.. java:import:: java.util.regex Matcher

.. java:import:: java.util.regex Pattern

TaskValidator
=============

.. java:package:: org.motechproject.tasks.validation
   :noindex:

.. java:type:: public final class TaskValidator extends GeneralValidator

   The \ ``TaskValidator``\  class is responsible for task validation

Fields
------
TASK
^^^^

.. java:field:: public static final String TASK
   :outertype: TaskValidator

Methods
-------
validate
^^^^^^^^

.. java:method:: public static Set<TaskError> validate(Task task)
   :outertype: TaskValidator

validateAction
^^^^^^^^^^^^^^

.. java:method:: public static Set<TaskError> validateAction(TaskActionInformation actionInformation, Channel channel)
   :outertype: TaskValidator

validateActionFields
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static Set<TaskError> validateActionFields(TaskActionInformation action, ActionEvent actionEvent, TriggerEvent trigger, Map<String, TaskDataProvider> providers)
   :outertype: TaskValidator

validateProvider
^^^^^^^^^^^^^^^^

.. java:method:: public static Set<TaskError> validateProvider(TaskDataProvider provider, DataSource dataSource, TriggerEvent trigger, Map<String, TaskDataProvider> availableProviders)
   :outertype: TaskValidator

validateTrigger
^^^^^^^^^^^^^^^

.. java:method:: public static Set<TaskError> validateTrigger(Task task, Channel channel)
   :outertype: TaskValidator

