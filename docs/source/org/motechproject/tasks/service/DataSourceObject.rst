.. java:import:: org.apache.commons.lang.builder EqualsBuilder

DataSourceObject
================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public class DataSourceObject

   DataSourceObject is the result of a \ :java:ref:`org.motechproject.commons.api.DataProvider`\  lookup.

Constructors
------------
DataSourceObject
^^^^^^^^^^^^^^^^

.. java:constructor:: public DataSourceObject(String objectId, Object objectValue, boolean failIfNotFound)
   :outertype: DataSourceObject

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: DataSourceObject

getObjectId
^^^^^^^^^^^

.. java:method:: public String getObjectId()
   :outertype: DataSourceObject

getObjectValue
^^^^^^^^^^^^^^

.. java:method:: public Object getObjectValue()
   :outertype: DataSourceObject

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: DataSourceObject

isFailIfNotFound
^^^^^^^^^^^^^^^^

.. java:method:: public boolean isFailIfNotFound()
   :outertype: DataSourceObject

