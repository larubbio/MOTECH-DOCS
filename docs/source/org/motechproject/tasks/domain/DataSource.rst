.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonIgnoreProperties

.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Objects

DataSource
==========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @JsonIgnoreProperties public class DataSource extends TaskConfigStep

Constructors
------------
DataSource
^^^^^^^^^^

.. java:constructor:: public DataSource()
   :outertype: DataSource

DataSource
^^^^^^^^^^

.. java:constructor:: public DataSource(String providerId, Long objectId, String type, String name, List<Lookup> lookup, boolean failIfDataNotFound)
   :outertype: DataSource

DataSource
^^^^^^^^^^

.. java:constructor:: public DataSource(String providerName, String providerId, Long objectId, String type, String name, List<Lookup> lookup, boolean failIfDataNotFound)
   :outertype: DataSource

DataSource
^^^^^^^^^^

.. java:constructor:: @Deprecated public DataSource(String providerId, Long objectId, String type, Lookup lookup, boolean failIfDataNotFound)
   :outertype: DataSource

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: DataSource

getLookup
^^^^^^^^^

.. java:method:: public List<Lookup> getLookup()
   :outertype: DataSource

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: DataSource

getObjectId
^^^^^^^^^^^

.. java:method:: public Long getObjectId()
   :outertype: DataSource

getProviderId
^^^^^^^^^^^^^

.. java:method:: public String getProviderId()
   :outertype: DataSource

getProviderName
^^^^^^^^^^^^^^^

.. java:method:: public String getProviderName()
   :outertype: DataSource

getType
^^^^^^^

.. java:method:: public String getType()
   :outertype: DataSource

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: DataSource

isFailIfDataNotFound
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isFailIfDataNotFound()
   :outertype: DataSource

objectEquals
^^^^^^^^^^^^

.. java:method:: @JsonIgnore public boolean objectEquals(String providerId, Long objectId, String type)
   :outertype: DataSource

setFailIfDataNotFound
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setFailIfDataNotFound(boolean failIfDataNotFound)
   :outertype: DataSource

setLookup
^^^^^^^^^

.. java:method:: public void setLookup(Object lookup)
   :outertype: DataSource

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: DataSource

setObjectId
^^^^^^^^^^^

.. java:method:: public void setObjectId(Long objectId)
   :outertype: DataSource

setProviderId
^^^^^^^^^^^^^

.. java:method:: public void setProviderId(String providerId)
   :outertype: DataSource

setProviderName
^^^^^^^^^^^^^^^

.. java:method:: public void setProviderName(String providerName)
   :outertype: DataSource

setType
^^^^^^^

.. java:method:: public void setType(String type)
   :outertype: DataSource

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: DataSource

