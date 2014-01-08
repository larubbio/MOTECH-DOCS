.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util List

RestOptions
===========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class RestOptions implements Serializable

   Class representing rest options of given entity.

Methods
-------
addField
^^^^^^^^

.. java:method:: public void addField(String value)
   :outertype: RestOptions

addLookup
^^^^^^^^^

.. java:method:: public void addLookup(String value)
   :outertype: RestOptions

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: RestOptions

   {@inheritDoc}

getFieldIds
^^^^^^^^^^^

.. java:method:: public List<String> getFieldIds()
   :outertype: RestOptions

getLookupIds
^^^^^^^^^^^^

.. java:method:: public List<String> getLookupIds()
   :outertype: RestOptions

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: RestOptions

   {@inheritDoc}

isCreate
^^^^^^^^

.. java:method:: public boolean isCreate()
   :outertype: RestOptions

isDelete
^^^^^^^^

.. java:method:: public boolean isDelete()
   :outertype: RestOptions

isRead
^^^^^^

.. java:method:: public boolean isRead()
   :outertype: RestOptions

isUpdate
^^^^^^^^

.. java:method:: public boolean isUpdate()
   :outertype: RestOptions

removeField
^^^^^^^^^^^

.. java:method:: public void removeField(String value)
   :outertype: RestOptions

removeLookup
^^^^^^^^^^^^

.. java:method:: public void removeLookup(String value)
   :outertype: RestOptions

setCreate
^^^^^^^^^

.. java:method:: public void setCreate(boolean create)
   :outertype: RestOptions

setDelete
^^^^^^^^^

.. java:method:: public void setDelete(boolean delete)
   :outertype: RestOptions

setFieldIds
^^^^^^^^^^^

.. java:method:: public void setFieldIds(List<String> fieldIds)
   :outertype: RestOptions

setLookupIds
^^^^^^^^^^^^

.. java:method:: public void setLookupIds(List<String> lookupIds)
   :outertype: RestOptions

setRead
^^^^^^^

.. java:method:: public void setRead(boolean read)
   :outertype: RestOptions

setUpdate
^^^^^^^^^

.. java:method:: public void setUpdate(boolean update)
   :outertype: RestOptions

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: RestOptions

   {@inheritDoc}

