.. java:import:: java.io Serializable

.. java:import:: java.util Objects

TaskEvent
=========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public abstract class TaskEvent implements Serializable

Constructors
------------
TaskEvent
^^^^^^^^^

.. java:constructor:: protected TaskEvent()
   :outertype: TaskEvent

TaskEvent
^^^^^^^^^

.. java:constructor:: protected TaskEvent(String description, String displayName, String subject)
   :outertype: TaskEvent

Methods
-------
containsParameter
^^^^^^^^^^^^^^^^^

.. java:method:: public abstract boolean containsParameter(String key)
   :outertype: TaskEvent

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskEvent

equalsSubject
^^^^^^^^^^^^^

.. java:method:: protected boolean equalsSubject(String subject)
   :outertype: TaskEvent

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: TaskEvent

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: TaskEvent

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: TaskEvent

hasSubject
^^^^^^^^^^

.. java:method:: public boolean hasSubject()
   :outertype: TaskEvent

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskEvent

setDescription
^^^^^^^^^^^^^^

.. java:method:: public void setDescription(String description)
   :outertype: TaskEvent

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: TaskEvent

setSubject
^^^^^^^^^^

.. java:method:: public void setSubject(String subject)
   :outertype: TaskEvent

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskEvent

