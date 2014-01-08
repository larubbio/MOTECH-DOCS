.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: org.springframework.util CollectionUtils

.. java:import:: java.util LinkedList

.. java:import:: java.util List

TrackingDto
===========

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class TrackingDto

   The \ ``TrackingDto``\  contains information about which fields and what kind of actions should be logged.

Methods
-------
addAction
^^^^^^^^^

.. java:method:: public void addAction(String action)
   :outertype: TrackingDto

addField
^^^^^^^^

.. java:method:: public void addField(String fieldId)
   :outertype: TrackingDto

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TrackingDto

   {@inheritDoc}

getActions
^^^^^^^^^^

.. java:method:: public List<String> getActions()
   :outertype: TrackingDto

getFields
^^^^^^^^^

.. java:method:: public List<String> getFields()
   :outertype: TrackingDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TrackingDto

   {@inheritDoc}

removeAction
^^^^^^^^^^^^

.. java:method:: public void removeAction(String action)
   :outertype: TrackingDto

removeField
^^^^^^^^^^^

.. java:method:: public void removeField(String fieldId)
   :outertype: TrackingDto

setActions
^^^^^^^^^^

.. java:method:: public void setActions(List<String> actions)
   :outertype: TrackingDto

setFields
^^^^^^^^^

.. java:method:: public void setFields(List<String> fields)
   :outertype: TrackingDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TrackingDto

   {@inheritDoc}

