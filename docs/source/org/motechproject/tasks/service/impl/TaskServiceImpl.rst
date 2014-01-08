.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.node ObjectNode

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain ChannelDeregisterEvent

.. java:import:: org.motechproject.tasks.domain ChannelRegisterEvent

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskConfigStep

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.events.constants EventSubjects

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TaskNotFoundException

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.repository AllTasks

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.motechproject.tasks.service TaskService

.. java:import:: org.motechproject.tasks.validation TaskValidator

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

.. java:import:: java.util SortedSet

TaskServiceImpl
===============

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: @Service public class TaskServiceImpl implements TaskService

   A \ :java:ref:`TaskService`\  that manages CRUD operations for a \ :java:ref:`Task`\  over a couchdb database. Expects channel registered,updated and deregistered events to be raised so that the associated tasks can be revalidated.

Constructors
------------
TaskServiceImpl
^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskServiceImpl(AllTasks allTasks, ChannelService channelService, TaskDataProviderService providerService, EventRelay eventRelay)
   :outertype: TaskServiceImpl

Methods
-------
activateTasksAfterChannelRegister
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void activateTasksAfterChannelRegister(MotechEvent motechEvent)
   :outertype: TaskServiceImpl

deactivateTasksAfterChannelDeregister
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void deactivateTasksAfterChannelDeregister(MotechEvent motechEvent)
   :outertype: TaskServiceImpl

deleteTask
^^^^^^^^^^

.. java:method:: @Override public void deleteTask(String taskId)
   :outertype: TaskServiceImpl

exportTask
^^^^^^^^^^

.. java:method:: @Override public String exportTask(String taskId)
   :outertype: TaskServiceImpl

findTasksForTrigger
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<Task> findTasksForTrigger(TriggerEvent trigger)
   :outertype: TaskServiceImpl

findTrigger
^^^^^^^^^^^

.. java:method:: @Override public TriggerEvent findTrigger(String subject) throws TriggerNotFoundException
   :outertype: TaskServiceImpl

getActionEventFor
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @Override public ActionEvent getActionEventFor(Task task) throws ActionNotFoundException
   :outertype: TaskServiceImpl

getActionEventFor
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ActionEvent getActionEventFor(TaskActionInformation taskActionInformation) throws ActionNotFoundException
   :outertype: TaskServiceImpl

getAllTasks
^^^^^^^^^^^

.. java:method:: @Override public List<Task> getAllTasks()
   :outertype: TaskServiceImpl

getTask
^^^^^^^

.. java:method:: @Override public Task getTask(String taskId)
   :outertype: TaskServiceImpl

importTask
^^^^^^^^^^

.. java:method:: @Override public void importTask(String json) throws IOException
   :outertype: TaskServiceImpl

save
^^^^

.. java:method:: @Override public void save(Task task)
   :outertype: TaskServiceImpl

validateTasksAfterChannelUpdate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void validateTasksAfterChannelUpdate(MotechEvent event)
   :outertype: TaskServiceImpl

validateTasksAfterTaskDataProviderUpdate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void validateTasksAfterTaskDataProviderUpdate(MotechEvent event)
   :outertype: TaskServiceImpl

