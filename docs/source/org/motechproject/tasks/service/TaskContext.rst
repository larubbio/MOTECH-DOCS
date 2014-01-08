.. java:import:: org.apache.commons.lang WordUtils

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.events.constants TaskFailureCause

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.lang.reflect Method

.. java:import:: java.util HashSet

.. java:import:: java.util Map

.. java:import:: java.util Set

TaskContext
===========

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public class TaskContext

   TaskContext holds task trigger event and data provider lookup objects that are used while executing filters/actions.

Constructors
------------
TaskContext
^^^^^^^^^^^

.. java:constructor:: public TaskContext(Task task, MotechEvent event, TaskActivityService activityService)
   :outertype: TaskContext

Methods
-------
addDataSourceObject
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void addDataSourceObject(String objectId, Object dataSourceObject, boolean failIfDataNotFound)
   :outertype: TaskContext

getDataSourceObjectValue
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Object getDataSourceObjectValue(String objectId, String field, String objectType) throws TaskHandlerException
   :outertype: TaskContext

getTask
^^^^^^^

.. java:method:: public Task getTask()
   :outertype: TaskContext

getTriggerParameters
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Map<String, Object> getTriggerParameters()
   :outertype: TaskContext

getTriggerValue
^^^^^^^^^^^^^^^

.. java:method:: public Object getTriggerValue(String key)
   :outertype: TaskContext

publishWarningActivity
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void publishWarningActivity(String message, String field)
   :outertype: TaskContext

