.. java:import:: org.apache.commons.lang.exception ExceptionUtils

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.domain TaskActivityType

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.motechproject.tasks.repository AllTaskActivities

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util Comparator

.. java:import:: java.util List

TaskActivityServiceImpl
=======================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: @Service public class TaskActivityServiceImpl implements TaskActivityService

Constructors
------------
TaskActivityServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskActivityServiceImpl(AllTaskActivities allTaskActivities)
   :outertype: TaskActivityServiceImpl

Methods
-------
addError
^^^^^^^^

.. java:method:: @Deprecated @Override public void addError(Task task, String message)
   :outertype: TaskActivityServiceImpl

addError
^^^^^^^^

.. java:method:: @Override public void addError(Task task, TaskHandlerException e)
   :outertype: TaskActivityServiceImpl

addSuccess
^^^^^^^^^^

.. java:method:: @Override public void addSuccess(Task task)
   :outertype: TaskActivityServiceImpl

addWarning
^^^^^^^^^^

.. java:method:: @Override public void addWarning(Task task)
   :outertype: TaskActivityServiceImpl

addWarning
^^^^^^^^^^

.. java:method:: @Override public void addWarning(Task task, String key, String field)
   :outertype: TaskActivityServiceImpl

addWarning
^^^^^^^^^^

.. java:method:: @Override public void addWarning(Task task, String key, String field, Exception e)
   :outertype: TaskActivityServiceImpl

deleteActivitiesForTask
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void deleteActivitiesForTask(String taskId)
   :outertype: TaskActivityServiceImpl

errorsFromLastRun
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<TaskActivity> errorsFromLastRun(Task task)
   :outertype: TaskActivityServiceImpl

getAllActivities
^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<TaskActivity> getAllActivities()
   :outertype: TaskActivityServiceImpl

getTaskActivities
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<TaskActivity> getTaskActivities(String taskId)
   :outertype: TaskActivityServiceImpl

