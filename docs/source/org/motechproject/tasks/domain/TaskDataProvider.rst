.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Objects

TaskDataProvider
================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class TaskDataProvider extends MotechBaseDataObject

   The \ ``TaskDataProvider``\  class cointains all informations about data providers used in tasks

Constructors
------------
TaskDataProvider
^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDataProvider()
   :outertype: TaskDataProvider

TaskDataProvider
^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDataProvider(String name, List<TaskDataProviderObject> objects)
   :outertype: TaskDataProvider

Methods
-------
containsProviderObject
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean containsProviderObject(String type)
   :outertype: TaskDataProvider

containsProviderObjectField
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean containsProviderObjectField(String type, String fieldKey)
   :outertype: TaskDataProvider

containsProviderObjectLookup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean containsProviderObjectLookup(String type, String lookupField)
   :outertype: TaskDataProvider

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskDataProvider

getKeyType
^^^^^^^^^^

.. java:method:: public String getKeyType(String key)
   :outertype: TaskDataProvider

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: TaskDataProvider

getObjects
^^^^^^^^^^

.. java:method:: public List<TaskDataProviderObject> getObjects()
   :outertype: TaskDataProvider

getProviderObject
^^^^^^^^^^^^^^^^^

.. java:method:: public TaskDataProviderObject getProviderObject(String type)
   :outertype: TaskDataProvider

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskDataProvider

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: TaskDataProvider

setObjects
^^^^^^^^^^

.. java:method:: public void setObjects(List<TaskDataProviderObject> objects)
   :outertype: TaskDataProvider

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskDataProvider

