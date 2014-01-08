.. java:import:: java.util ArrayList

.. java:import:: java.util List

EntityRecord
============

.. java:package:: org.motechproject.mds.web.domain
   :noindex:

.. java:type:: public class EntityRecord

   Represents single entity instance (used in jqGrid)

Constructors
------------
EntityRecord
^^^^^^^^^^^^

.. java:constructor:: public EntityRecord(String id, String entitySchemaId, List<FieldRecord> fields)
   :outertype: EntityRecord

EntityRecord
^^^^^^^^^^^^

.. java:constructor:: public EntityRecord()
   :outertype: EntityRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: EntityRecord

getEntitySchemaId
^^^^^^^^^^^^^^^^^

.. java:method:: public String getEntitySchemaId()
   :outertype: EntityRecord

getFields
^^^^^^^^^

.. java:method:: public List<FieldRecord> getFields()
   :outertype: EntityRecord

getId
^^^^^

.. java:method:: public String getId()
   :outertype: EntityRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: EntityRecord

setEntitySchemaId
^^^^^^^^^^^^^^^^^

.. java:method:: public void setEntitySchemaId(String entitySchemaId)
   :outertype: EntityRecord

setFields
^^^^^^^^^

.. java:method:: public void setFields(List<FieldRecord> fields)
   :outertype: EntityRecord

setId
^^^^^

.. java:method:: public void setId(String id)
   :outertype: EntityRecord

