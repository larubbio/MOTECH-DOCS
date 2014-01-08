.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Objects

TaskDataProviderObject
======================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class TaskDataProviderObject implements Serializable

Constructors
------------
TaskDataProviderObject
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDataProviderObject()
   :outertype: TaskDataProviderObject

TaskDataProviderObject
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDataProviderObject(String displayName, String type, List<LookupFieldsParameter> lookupFields, List<FieldParameter> fields)
   :outertype: TaskDataProviderObject

Methods
-------
containsField
^^^^^^^^^^^^^

.. java:method:: public boolean containsField(String fieldKey)
   :outertype: TaskDataProviderObject

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskDataProviderObject

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: TaskDataProviderObject

getFields
^^^^^^^^^

.. java:method:: public List<FieldParameter> getFields()
   :outertype: TaskDataProviderObject

getLookupFields
^^^^^^^^^^^^^^^

.. java:method:: public List<LookupFieldsParameter> getLookupFields()
   :outertype: TaskDataProviderObject

getType
^^^^^^^

.. java:method:: public String getType()
   :outertype: TaskDataProviderObject

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskDataProviderObject

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: TaskDataProviderObject

setFields
^^^^^^^^^

.. java:method:: public void setFields(List<FieldParameter> fields)
   :outertype: TaskDataProviderObject

setLookupFields
^^^^^^^^^^^^^^^

.. java:method:: public void setLookupFields(List<Object> lookupFields)
   :outertype: TaskDataProviderObject

setType
^^^^^^^

.. java:method:: public void setType(String type)
   :outertype: TaskDataProviderObject

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskDataProviderObject

