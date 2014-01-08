.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain KeyInformation

.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util Collection

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util SortedSet

TaskActionExecutor
==================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type::  class TaskActionExecutor

   Builds action parameters from \ :java:ref:`TaskContext`\  and executes the action by invoking its service or raising its event.

Constructors
------------
TaskActionExecutor
^^^^^^^^^^^^^^^^^^

.. java:constructor::  TaskActionExecutor(TaskService taskService, TaskActivityService activityService, EventRelay eventRelay)
   :outertype: TaskActionExecutor

Methods
-------
createParameters
^^^^^^^^^^^^^^^^

.. java:method::  Map<String, Object> createParameters(TaskActionInformation info, ActionEvent action) throws TaskHandlerException
   :outertype: TaskActionExecutor

execute
^^^^^^^

.. java:method::  void execute(Task task, TaskActionInformation actionInformation, TaskContext taskContext) throws TaskHandlerException
   :outertype: TaskActionExecutor

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method::  void setBundleContext(BundleContext bundleContext)
   :outertype: TaskActionExecutor

