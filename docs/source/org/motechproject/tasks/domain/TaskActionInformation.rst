.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util Objects

TaskActionInformation
=====================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class TaskActionInformation extends TaskEventInformation

   Represents an action event configured with a \ :java:ref:`Task`\

Constructors
------------
TaskActionInformation
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskActionInformation()
   :outertype: TaskActionInformation

TaskActionInformation
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskActionInformation(String displayName, String channelName, String moduleName, String moduleVersion, String subject)
   :outertype: TaskActionInformation

TaskActionInformation
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskActionInformation(String displayName, String channelName, String moduleName, String moduleVersion, String subject, Map<String, String> values)
   :outertype: TaskActionInformation

TaskActionInformation
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskActionInformation(String displayName, String channelName, String moduleName, String moduleVersion, String serviceInterface, String serviceMethod)
   :outertype: TaskActionInformation

TaskActionInformation
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskActionInformation(String displayName, String channelName, String moduleName, String moduleVersion, String subject, String serviceInterface, String serviceMethod, Map<String, String> values)
   :outertype: TaskActionInformation

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskActionInformation

getServiceInterface
^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceInterface()
   :outertype: TaskActionInformation

getServiceMethod
^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceMethod()
   :outertype: TaskActionInformation

getValues
^^^^^^^^^

.. java:method:: public Map<String, String> getValues()
   :outertype: TaskActionInformation

hasService
^^^^^^^^^^

.. java:method:: public boolean hasService()
   :outertype: TaskActionInformation

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskActionInformation

setServiceInterface
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setServiceInterface(String serviceInterface)
   :outertype: TaskActionInformation

setServiceMethod
^^^^^^^^^^^^^^^^

.. java:method:: public void setServiceMethod(String serviceMethod)
   :outertype: TaskActionInformation

setValues
^^^^^^^^^

.. java:method:: public void setValues(Map<String, String> values)
   :outertype: TaskActionInformation

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskActionInformation

