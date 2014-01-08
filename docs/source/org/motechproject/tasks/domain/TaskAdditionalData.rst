.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: java.io Serializable

.. java:import:: java.util Objects

TaskAdditionalData
==================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @Deprecated public class TaskAdditionalData implements Serializable

Constructors
------------
TaskAdditionalData
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskAdditionalData()
   :outertype: TaskAdditionalData

TaskAdditionalData
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskAdditionalData(Long id, String type, String lookupField, String lookupValue, boolean failIfDataNotFound)
   :outertype: TaskAdditionalData

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskAdditionalData

getId
^^^^^

.. java:method:: public Long getId()
   :outertype: TaskAdditionalData

getLookupField
^^^^^^^^^^^^^^

.. java:method:: public String getLookupField()
   :outertype: TaskAdditionalData

getLookupValue
^^^^^^^^^^^^^^

.. java:method:: public String getLookupValue()
   :outertype: TaskAdditionalData

getType
^^^^^^^

.. java:method:: public String getType()
   :outertype: TaskAdditionalData

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskAdditionalData

isFailIfDataNotFound
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isFailIfDataNotFound()
   :outertype: TaskAdditionalData

objectEquals
^^^^^^^^^^^^

.. java:method:: @JsonIgnore public boolean objectEquals(Long id, String type)
   :outertype: TaskAdditionalData

setFailIfDataNotFound
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setFailIfDataNotFound(boolean failIfDataNotFound)
   :outertype: TaskAdditionalData

setId
^^^^^

.. java:method:: public void setId(Long id)
   :outertype: TaskAdditionalData

setLookupField
^^^^^^^^^^^^^^

.. java:method:: public void setLookupField(String lookupField)
   :outertype: TaskAdditionalData

setLookupValue
^^^^^^^^^^^^^^

.. java:method:: public void setLookupValue(String lookupValue)
   :outertype: TaskAdditionalData

setType
^^^^^^^

.. java:method:: public void setType(String type)
   :outertype: TaskAdditionalData

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskAdditionalData

