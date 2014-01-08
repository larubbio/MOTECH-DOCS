.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: org.springframework.util CollectionUtils

.. java:import:: java.util LinkedList

.. java:import:: java.util List

FieldDto
========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class FieldDto

   The \ ``FieldDto``\  class contains information about an existing field in an entity.

Constructors
------------
FieldDto
^^^^^^^^

.. java:constructor:: public FieldDto()
   :outertype: FieldDto

FieldDto
^^^^^^^^

.. java:constructor:: public FieldDto(String id, String entityId, TypeDto type, FieldBasicDto basic, List<MetadataDto> metadata, FieldValidationDto validation, List<SettingDto> settings)
   :outertype: FieldDto

Methods
-------
addEmptyMetadata
^^^^^^^^^^^^^^^^

.. java:method:: public void addEmptyMetadata()
   :outertype: FieldDto

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: FieldDto

   {@inheritDoc}

getBasic
^^^^^^^^

.. java:method:: public FieldBasicDto getBasic()
   :outertype: FieldDto

getEntityId
^^^^^^^^^^^

.. java:method:: public String getEntityId()
   :outertype: FieldDto

getId
^^^^^

.. java:method:: public String getId()
   :outertype: FieldDto

getMetadata
^^^^^^^^^^^

.. java:method:: public List<MetadataDto> getMetadata()
   :outertype: FieldDto

getSettings
^^^^^^^^^^^

.. java:method:: public List<SettingDto> getSettings()
   :outertype: FieldDto

getType
^^^^^^^

.. java:method:: public TypeDto getType()
   :outertype: FieldDto

getValidation
^^^^^^^^^^^^^

.. java:method:: public FieldValidationDto getValidation()
   :outertype: FieldDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: FieldDto

   {@inheritDoc}

removeMetadata
^^^^^^^^^^^^^^

.. java:method:: public void removeMetadata(Integer idx)
   :outertype: FieldDto

setBasic
^^^^^^^^

.. java:method:: public void setBasic(FieldBasicDto basic)
   :outertype: FieldDto

setEntityId
^^^^^^^^^^^

.. java:method:: public void setEntityId(String entityId)
   :outertype: FieldDto

setId
^^^^^

.. java:method:: public void setId(String id)
   :outertype: FieldDto

setMetadata
^^^^^^^^^^^

.. java:method:: public void setMetadata(List<MetadataDto> metadata)
   :outertype: FieldDto

setSettings
^^^^^^^^^^^

.. java:method:: public void setSettings(List<SettingDto> settings)
   :outertype: FieldDto

setType
^^^^^^^

.. java:method:: public void setType(TypeDto type)
   :outertype: FieldDto

setValidation
^^^^^^^^^^^^^

.. java:method:: public void setValidation(FieldValidationDto validation)
   :outertype: FieldDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: FieldDto

   {@inheritDoc}

