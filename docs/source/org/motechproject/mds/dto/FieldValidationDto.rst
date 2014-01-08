.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: java.util Collections

.. java:import:: java.util LinkedList

.. java:import:: java.util List

FieldValidationDto
==================

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class FieldValidationDto

   The \ ``FieldValidationDto``\  class contains information about validation criteria for field.

Fields
------
DOUBLE
^^^^^^

.. java:field:: public static final FieldValidationDto DOUBLE
   :outertype: FieldValidationDto

   Constant \ ``DOUBLE``\  contains validation criteria for double type.

INTEGER
^^^^^^^

.. java:field:: public static final FieldValidationDto INTEGER
   :outertype: FieldValidationDto

   Constant \ ``INTEGER``\  contains validation criteria for integer type.

STRING
^^^^^^

.. java:field:: public static final FieldValidationDto STRING
   :outertype: FieldValidationDto

   Constant \ ``STRING``\  contains validation criteria for string type.

Constructors
------------
FieldValidationDto
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public FieldValidationDto()
   :outertype: FieldValidationDto

FieldValidationDto
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public FieldValidationDto(ValidationCriterionDto... criteria)
   :outertype: FieldValidationDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: FieldValidationDto

   {@inheritDoc}

getCriteria
^^^^^^^^^^^

.. java:method:: public List<ValidationCriterionDto> getCriteria()
   :outertype: FieldValidationDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: FieldValidationDto

   {@inheritDoc}

setCriteria
^^^^^^^^^^^

.. java:method:: public void setCriteria(List<ValidationCriterionDto> criteria)
   :outertype: FieldValidationDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: FieldValidationDto

   {@inheritDoc}

