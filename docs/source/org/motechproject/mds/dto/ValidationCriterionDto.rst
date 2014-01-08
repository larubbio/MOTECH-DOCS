.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

ValidationCriterionDto
======================

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class ValidationCriterionDto

   The \ ``ValidationCriterionDto``\  contains information about single criterion for field validation.

Constructors
------------
ValidationCriterionDto
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ValidationCriterionDto()
   :outertype: ValidationCriterionDto

ValidationCriterionDto
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ValidationCriterionDto(String displayName, TypeDto type)
   :outertype: ValidationCriterionDto

ValidationCriterionDto
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ValidationCriterionDto(String displayName, TypeDto type, Object value, boolean enabled)
   :outertype: ValidationCriterionDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ValidationCriterionDto

   {@inheritDoc}

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: ValidationCriterionDto

getType
^^^^^^^

.. java:method:: public TypeDto getType()
   :outertype: ValidationCriterionDto

getValue
^^^^^^^^

.. java:method:: public Object getValue()
   :outertype: ValidationCriterionDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ValidationCriterionDto

   {@inheritDoc}

isEnabled
^^^^^^^^^

.. java:method:: public boolean isEnabled()
   :outertype: ValidationCriterionDto

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: ValidationCriterionDto

setEnabled
^^^^^^^^^^

.. java:method:: public void setEnabled(boolean enabled)
   :outertype: ValidationCriterionDto

setType
^^^^^^^

.. java:method:: public void setType(TypeDto type)
   :outertype: ValidationCriterionDto

setValue
^^^^^^^^

.. java:method:: public void setValue(Object value)
   :outertype: ValidationCriterionDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ValidationCriterionDto

   {@inheritDoc}

