.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.apache.commons.lang.builder ToStringBuilder

.. java:import:: org.apache.commons.lang.builder ToStringStyle

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AdvancedSettingsDto
===================

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class AdvancedSettingsDto

   The \ ``AdvancedSettingsDto``\  contains information about advanced settings of an entity.

Methods
-------
addNewIndex
^^^^^^^^^^^

.. java:method:: public void addNewIndex()
   :outertype: AdvancedSettingsDto

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: AdvancedSettingsDto

   {@inheritDoc}

getBrowsing
^^^^^^^^^^^

.. java:method:: public BrowsingSettingsDto getBrowsing()
   :outertype: AdvancedSettingsDto

getEntityId
^^^^^^^^^^^

.. java:method:: public String getEntityId()
   :outertype: AdvancedSettingsDto

getId
^^^^^

.. java:method:: public String getId()
   :outertype: AdvancedSettingsDto

getIndexes
^^^^^^^^^^

.. java:method:: public List<LookupDto> getIndexes()
   :outertype: AdvancedSettingsDto

getRestOptions
^^^^^^^^^^^^^^

.. java:method:: public RestOptions getRestOptions()
   :outertype: AdvancedSettingsDto

getTracking
^^^^^^^^^^^

.. java:method:: public TrackingDto getTracking()
   :outertype: AdvancedSettingsDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AdvancedSettingsDto

   {@inheritDoc}

removeIndex
^^^^^^^^^^^

.. java:method:: public void removeIndex(Integer idx)
   :outertype: AdvancedSettingsDto

setBrowsing
^^^^^^^^^^^

.. java:method:: public void setBrowsing(BrowsingSettingsDto browsing)
   :outertype: AdvancedSettingsDto

setEntityId
^^^^^^^^^^^

.. java:method:: public void setEntityId(String entityId)
   :outertype: AdvancedSettingsDto

setId
^^^^^

.. java:method:: public void setId(String id)
   :outertype: AdvancedSettingsDto

setIndexes
^^^^^^^^^^

.. java:method:: public void setIndexes(List<LookupDto> indexes)
   :outertype: AdvancedSettingsDto

setRestOptions
^^^^^^^^^^^^^^

.. java:method:: public void setRestOptions(RestOptions restOptions)
   :outertype: AdvancedSettingsDto

setTracking
^^^^^^^^^^^

.. java:method:: public void setTracking(TrackingDto tracking)
   :outertype: AdvancedSettingsDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: AdvancedSettingsDto

   {@inheritDoc}

