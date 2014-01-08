.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateTimeSourceUtil

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: java.util Arrays

.. java:import:: java.util Objects

TaskActivity
============

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class TaskActivity extends MotechBaseDataObject implements Comparable<TaskActivity>

Constructors
------------
TaskActivity
^^^^^^^^^^^^

.. java:constructor:: public TaskActivity()
   :outertype: TaskActivity

TaskActivity
^^^^^^^^^^^^

.. java:constructor:: public TaskActivity(String message, String task, TaskActivityType activityType)
   :outertype: TaskActivity

TaskActivity
^^^^^^^^^^^^

.. java:constructor:: public TaskActivity(String message, String field, String task, TaskActivityType activityType)
   :outertype: TaskActivity

TaskActivity
^^^^^^^^^^^^

.. java:constructor:: public TaskActivity(String message, String fields, String task, TaskActivityType activityType)
   :outertype: TaskActivity

TaskActivity
^^^^^^^^^^^^

.. java:constructor:: public TaskActivity(String message, String fields, String task, TaskActivityType activityType, String stackTraceElement)
   :outertype: TaskActivity

Methods
-------
compareTo
^^^^^^^^^

.. java:method:: @Override public int compareTo(TaskActivity o)
   :outertype: TaskActivity

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskActivity

getActivityType
^^^^^^^^^^^^^^^

.. java:method:: public TaskActivityType getActivityType()
   :outertype: TaskActivity

getDate
^^^^^^^

.. java:method:: public DateTime getDate()
   :outertype: TaskActivity

getFields
^^^^^^^^^

.. java:method:: public String getFields()
   :outertype: TaskActivity

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: TaskActivity

getStackTraceElement
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getStackTraceElement()
   :outertype: TaskActivity

getTask
^^^^^^^

.. java:method:: public String getTask()
   :outertype: TaskActivity

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskActivity

setActivityType
^^^^^^^^^^^^^^^

.. java:method:: public void setActivityType(TaskActivityType activityType)
   :outertype: TaskActivity

setDate
^^^^^^^

.. java:method:: public void setDate(DateTime date)
   :outertype: TaskActivity

setField
^^^^^^^^

.. java:method:: public void setField(String field)
   :outertype: TaskActivity

setFields
^^^^^^^^^

.. java:method:: public void setFields(String fields)
   :outertype: TaskActivity

setMessage
^^^^^^^^^^

.. java:method:: public void setMessage(String message)
   :outertype: TaskActivity

setStackTraceElement
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setStackTraceElement(String stackTraceElement)
   :outertype: TaskActivity

setTask
^^^^^^^

.. java:method:: public void setTask(String task)
   :outertype: TaskActivity

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskActivity

