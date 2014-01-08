.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

FieldBasicDto
=============

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class FieldBasicDto

   The \ ``FieldBasicDto``\  contains basic information about a field.

Constructors
------------
FieldBasicDto
^^^^^^^^^^^^^

.. java:constructor:: public FieldBasicDto()
   :outertype: FieldBasicDto

FieldBasicDto
^^^^^^^^^^^^^

.. java:constructor:: public FieldBasicDto(String displayName, String name)
   :outertype: FieldBasicDto

FieldBasicDto
^^^^^^^^^^^^^

.. java:constructor:: public FieldBasicDto(String displayName, String name, boolean required, Object defaultValue, String tooltip)
   :outertype: FieldBasicDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: FieldBasicDto

   {@inheritDoc}

getDefaultValue
^^^^^^^^^^^^^^^

.. java:method:: public Object getDefaultValue()
   :outertype: FieldBasicDto

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: FieldBasicDto

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: FieldBasicDto

getTooltip
^^^^^^^^^^

.. java:method:: public String getTooltip()
   :outertype: FieldBasicDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: FieldBasicDto

   {@inheritDoc}

isRequired
^^^^^^^^^^

.. java:method:: public boolean isRequired()
   :outertype: FieldBasicDto

setDefaultValue
^^^^^^^^^^^^^^^

.. java:method:: public void setDefaultValue(Object defaultValue)
   :outertype: FieldBasicDto

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: FieldBasicDto

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: FieldBasicDto

setRequired
^^^^^^^^^^^

.. java:method:: public void setRequired(boolean required)
   :outertype: FieldBasicDto

setTooltip
^^^^^^^^^^

.. java:method:: public void setTooltip(String tooltip)
   :outertype: FieldBasicDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: FieldBasicDto

   {@inheritDoc}

