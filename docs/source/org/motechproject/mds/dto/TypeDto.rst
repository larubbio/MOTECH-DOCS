.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: java.util Date

.. java:import:: java.util List

TypeDto
=======

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class TypeDto

   The \ ``TypeDto``\  class contains information about an available field in an entity.

Fields
------
BOOLEAN
^^^^^^^

.. java:field:: public static final TypeDto BOOLEAN
   :outertype: TypeDto

   Constant \ ``BOOLEAN``\  presents a boolean type.

DATE
^^^^

.. java:field:: public static final TypeDto DATE
   :outertype: TypeDto

   Constant \ ``DATE``\  presents a date type.

DATETIME
^^^^^^^^

.. java:field:: public static final TypeDto DATETIME
   :outertype: TypeDto

   Constant \ ``DATETIME``\  presents a datetime type.

DOUBLE
^^^^^^

.. java:field:: public static final TypeDto DOUBLE
   :outertype: TypeDto

   Constant \ ``DOUBLE``\  presents a double/decimal type.

INTEGER
^^^^^^^

.. java:field:: public static final TypeDto INTEGER
   :outertype: TypeDto

   Constant \ ``INTEGER``\  presents a integer type.

LIST
^^^^

.. java:field:: public static final TypeDto LIST
   :outertype: TypeDto

   Constant \ ``LIST``\  presents a list/combobox type.

STRING
^^^^^^

.. java:field:: public static final TypeDto STRING
   :outertype: TypeDto

   Constant \ ``STRING``\  presents a string type.

TIME
^^^^

.. java:field:: public static final TypeDto TIME
   :outertype: TypeDto

   Constant \ ``TIME``\  presents a time type.

Constructors
------------
TypeDto
^^^^^^^

.. java:constructor:: public TypeDto()
   :outertype: TypeDto

TypeDto
^^^^^^^

.. java:constructor:: public TypeDto(String displayName, String description, String typeClass)
   :outertype: TypeDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TypeDto

   {@inheritDoc}

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: TypeDto

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: TypeDto

getTypeClass
^^^^^^^^^^^^

.. java:method:: public String getTypeClass()
   :outertype: TypeDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TypeDto

   {@inheritDoc}

setDescription
^^^^^^^^^^^^^^

.. java:method:: public void setDescription(String description)
   :outertype: TypeDto

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: TypeDto

setTypeClass
^^^^^^^^^^^^

.. java:method:: public void setTypeClass(String typeClass)
   :outertype: TypeDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TypeDto

   {@inheritDoc}

