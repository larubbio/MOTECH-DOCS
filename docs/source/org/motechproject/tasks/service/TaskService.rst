.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

.. java:import:: java.io IOException

.. java:import:: java.util List

TaskService
===========

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public interface TaskService

Methods
-------
deleteTask
^^^^^^^^^^

.. java:method::  void deleteTask(String taskId)
   :outertype: TaskService

exportTask
^^^^^^^^^^

.. java:method::  String exportTask(String taskId)
   :outertype: TaskService

findTasksForTrigger
^^^^^^^^^^^^^^^^^^^

.. java:method::  List<Task> findTasksForTrigger(TriggerEvent trigger)
   :outertype: TaskService

findTrigger
^^^^^^^^^^^

.. java:method::  TriggerEvent findTrigger(String subject) throws TriggerNotFoundException
   :outertype: TaskService

getActionEventFor
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated  ActionEvent getActionEventFor(Task task) throws ActionNotFoundException
   :outertype: TaskService

getActionEventFor
^^^^^^^^^^^^^^^^^

.. java:method::  ActionEvent getActionEventFor(TaskActionInformation taskActionInformation) throws ActionNotFoundException
   :outertype: TaskService

getAllTasks
^^^^^^^^^^^

.. java:method::  List<Task> getAllTasks()
   :outertype: TaskService

getTask
^^^^^^^

.. java:method::  Task getTask(String taskId)
   :outertype: TaskService

importTask
^^^^^^^^^^

.. java:method::  void importTask(String json) throws IOException
   :outertype: TaskService

save
^^^^

.. java:method::  void save(Task task)
   :outertype: TaskService

