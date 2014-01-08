.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.codehaus.jackson.map.annotate JsonDeserialize

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.tasks.json TaskDeserializer

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Objects

.. java:import:: java.util Set

Task
====

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @TypeDiscriminator @JsonDeserialize public class Task extends MotechBaseDataObject

   A task is set of actions that are executed in response to a trigger. The actions and the trigger are defined by their respective \ :java:ref:`Channel`\ s.

Constructors
------------
Task
^^^^

.. java:constructor:: public Task()
   :outertype: Task

Task
^^^^

.. java:constructor:: @Deprecated public Task(String name, TaskEventInformation trigger, TaskActionInformation action, Map<String, String> actionInputFields)
   :outertype: Task

Task
^^^^

.. java:constructor:: @Deprecated public Task(String name, TaskEventInformation trigger, TaskActionInformation action, Map<String, String> actionInputFields, List<Filter> filters, Map<String, List<TaskAdditionalData>> additionalData, boolean enabled)
   :outertype: Task

Task
^^^^

.. java:constructor:: public Task(String name, TaskEventInformation trigger, List<TaskActionInformation> actions)
   :outertype: Task

Task
^^^^

.. java:constructor:: public Task(String name, TaskEventInformation trigger, List<TaskActionInformation> actions, TaskConfig taskConfig, boolean enabled, boolean hasRegisteredChannel)
   :outertype: Task

Methods
-------
addAction
^^^^^^^^^

.. java:method:: public void addAction(TaskActionInformation action)
   :outertype: Task

addValidationErrors
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void addValidationErrors(Set<TaskError> validationErrors)
   :outertype: Task

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Task

getAction
^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public TaskActionInformation getAction()
   :outertype: Task

getActionInputFields
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public Map<String, String> getActionInputFields()
   :outertype: Task

getActions
^^^^^^^^^^

.. java:method:: public List<TaskActionInformation> getActions()
   :outertype: Task

getAdditionalData
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public Map<String, List<TaskAdditionalData>> getAdditionalData()
   :outertype: Task

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: Task

getFilters
^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public List<Filter> getFilters()
   :outertype: Task

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: Task

getTaskConfig
^^^^^^^^^^^^^

.. java:method:: public TaskConfig getTaskConfig()
   :outertype: Task

getTrigger
^^^^^^^^^^

.. java:method:: public TaskEventInformation getTrigger()
   :outertype: Task

getValidationErrors
^^^^^^^^^^^^^^^^^^^

.. java:method:: public Set<TaskError> getValidationErrors()
   :outertype: Task

hasRegisteredChannel
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonProperty public boolean hasRegisteredChannel()
   :outertype: Task

hasValidationErrors
^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean hasValidationErrors()
   :outertype: Task

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Task

isEnabled
^^^^^^^^^

.. java:method:: public boolean isEnabled()
   :outertype: Task

removeValidationError
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeValidationError(String message)
   :outertype: Task

setAction
^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public void setAction(TaskActionInformation action)
   :outertype: Task

setActionInputFields
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public void setActionInputFields(Map<String, String> actionInputFields)
   :outertype: Task

setActions
^^^^^^^^^^

.. java:method:: public void setActions(List<TaskActionInformation> actions)
   :outertype: Task

setAdditionalData
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public void setAdditionalData(Map<String, List<TaskAdditionalData>> additionalData)
   :outertype: Task

setDescription
^^^^^^^^^^^^^^

.. java:method:: public void setDescription(String description)
   :outertype: Task

setEnabled
^^^^^^^^^^

.. java:method:: public void setEnabled(boolean enabled)
   :outertype: Task

setFilters
^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public void setFilters(List<Filter> filters)
   :outertype: Task

setHasRegisteredChannel
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonProperty public void setHasRegisteredChannel(boolean hasRegisteredChannel)
   :outertype: Task

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: Task

setTaskConfig
^^^^^^^^^^^^^

.. java:method:: public void setTaskConfig(TaskConfig taskConfig)
   :outertype: Task

setTrigger
^^^^^^^^^^

.. java:method:: public void setTrigger(TaskEventInformation trigger)
   :outertype: Task

setValidationErrors
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setValidationErrors(Set<TaskError> validationErrors)
   :outertype: Task

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: Task

