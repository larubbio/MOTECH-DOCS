.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.util List

TaskActivityService
===================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public interface TaskActivityService

Methods
-------
addError
^^^^^^^^

.. java:method:: @Deprecated  void addError(Task task, String message)
   :outertype: TaskActivityService

addError
^^^^^^^^

.. java:method::  void addError(Task task, TaskHandlerException e)
   :outertype: TaskActivityService

addSuccess
^^^^^^^^^^

.. java:method::  void addSuccess(Task task)
   :outertype: TaskActivityService

addWarning
^^^^^^^^^^

.. java:method::  void addWarning(Task task)
   :outertype: TaskActivityService

addWarning
^^^^^^^^^^

.. java:method::  void addWarning(Task task, String key, String value)
   :outertype: TaskActivityService

addWarning
^^^^^^^^^^

.. java:method::  void addWarning(Task task, String key, String field, Exception e)
   :outertype: TaskActivityService

deleteActivitiesForTask
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void deleteActivitiesForTask(String taskId)
   :outertype: TaskActivityService

errorsFromLastRun
^^^^^^^^^^^^^^^^^

.. java:method::  List<TaskActivity> errorsFromLastRun(Task task)
   :outertype: TaskActivityService

getAllActivities
^^^^^^^^^^^^^^^^

.. java:method::  List<TaskActivity> getAllActivities()
   :outertype: TaskActivityService

getTaskActivities
^^^^^^^^^^^^^^^^^

.. java:method::  List<TaskActivity> getTaskActivities(String taskId)
   :outertype: TaskActivityService

