.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: org.springframework.util CollectionUtils

.. java:import:: java.util Collections

.. java:import:: java.util LinkedList

.. java:import:: java.util List

SettingDto
==========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class SettingDto

   The \ ``SettingDto``\  contains information about a single setting inside a field.

Constructors
------------
SettingDto
^^^^^^^^^^

.. java:constructor:: public SettingDto()
   :outertype: SettingDto

SettingDto
^^^^^^^^^^

.. java:constructor:: public SettingDto(String name, Object value, TypeDto type, SettingOptions... options)
   :outertype: SettingDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: SettingDto

   {@inheritDoc}

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: SettingDto

getOptions
^^^^^^^^^^

.. java:method:: public List<SettingOptions> getOptions()
   :outertype: SettingDto

getType
^^^^^^^

.. java:method:: public TypeDto getType()
   :outertype: SettingDto

getValue
^^^^^^^^

.. java:method:: public Object getValue()
   :outertype: SettingDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: SettingDto

   {@inheritDoc}

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: SettingDto

setOptions
^^^^^^^^^^

.. java:method:: public void setOptions(List<SettingOptions> options)
   :outertype: SettingDto

setType
^^^^^^^

.. java:method:: public void setType(TypeDto type)
   :outertype: SettingDto

setValue
^^^^^^^^

.. java:method:: public void setValue(Object value)
   :outertype: SettingDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: SettingDto

   {@inheritDoc}

