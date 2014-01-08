.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: java.util LinkedList

.. java:import:: java.util List

LookupDto
=========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class LookupDto

   The \ ``LookupDto``\  class contains information about single lookup defined by user

Constructors
------------
LookupDto
^^^^^^^^^

.. java:constructor:: public LookupDto()
   :outertype: LookupDto

LookupDto
^^^^^^^^^

.. java:constructor:: public LookupDto(String lookupName, boolean singleObjectReturn)
   :outertype: LookupDto

LookupDto
^^^^^^^^^

.. java:constructor:: public LookupDto(String lookupName, boolean singleObjectReturn, List<String> fieldList)
   :outertype: LookupDto

Methods
-------
addField
^^^^^^^^

.. java:method:: public void addField(String field)
   :outertype: LookupDto

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: LookupDto

   {@inheritDoc}

getFieldList
^^^^^^^^^^^^

.. java:method:: public List<String> getFieldList()
   :outertype: LookupDto

getLookupName
^^^^^^^^^^^^^

.. java:method:: public String getLookupName()
   :outertype: LookupDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: LookupDto

   {@inheritDoc}

insertField
^^^^^^^^^^^

.. java:method:: public void insertField(Integer idx, String fieldId)
   :outertype: LookupDto

isSingleObjectReturn
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isSingleObjectReturn()
   :outertype: LookupDto

removeField
^^^^^^^^^^^

.. java:method:: public void removeField(String fieldId)
   :outertype: LookupDto

setFieldList
^^^^^^^^^^^^

.. java:method:: public void setFieldList(List<String> fieldList)
   :outertype: LookupDto

setLookupName
^^^^^^^^^^^^^

.. java:method:: public void setLookupName(String lookupName)
   :outertype: LookupDto

setSingleObjectReturn
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setSingleObjectReturn(boolean singleObjectReturn)
   :outertype: LookupDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: LookupDto

   {@inheritDoc}

