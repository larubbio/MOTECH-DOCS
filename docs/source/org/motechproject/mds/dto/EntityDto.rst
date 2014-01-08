.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

EntityDto
=========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class EntityDto

   The \ ``EntityDto``\  class contains only basic information about an entity like id, name, module and namespace.

Constructors
------------
EntityDto
^^^^^^^^^

.. java:constructor:: public EntityDto()
   :outertype: EntityDto

EntityDto
^^^^^^^^^

.. java:constructor:: public EntityDto(String id, String name)
   :outertype: EntityDto

EntityDto
^^^^^^^^^

.. java:constructor:: public EntityDto(String id, String name, String module)
   :outertype: EntityDto

EntityDto
^^^^^^^^^

.. java:constructor:: public EntityDto(String id, String name, String module, String namespace)
   :outertype: EntityDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: EntityDto

   {@inheritDoc}

getId
^^^^^

.. java:method:: public String getId()
   :outertype: EntityDto

getModule
^^^^^^^^^

.. java:method:: public String getModule()
   :outertype: EntityDto

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: EntityDto

getNamespace
^^^^^^^^^^^^

.. java:method:: public String getNamespace()
   :outertype: EntityDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: EntityDto

   {@inheritDoc}

isDraft
^^^^^^^

.. java:method:: public boolean isDraft()
   :outertype: EntityDto

isReadOnly
^^^^^^^^^^

.. java:method:: public boolean isReadOnly()
   :outertype: EntityDto

setDraft
^^^^^^^^

.. java:method:: public void setDraft(boolean draft)
   :outertype: EntityDto

setId
^^^^^

.. java:method:: public void setId(String id)
   :outertype: EntityDto

setModule
^^^^^^^^^

.. java:method:: public void setModule(String module)
   :outertype: EntityDto

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: EntityDto

setNamespace
^^^^^^^^^^^^

.. java:method:: public void setNamespace(String namespace)
   :outertype: EntityDto

setReadOnly
^^^^^^^^^^^

.. java:method:: public void setReadOnly(boolean readOnly)
   :outertype: EntityDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: EntityDto

   {@inheritDoc}

