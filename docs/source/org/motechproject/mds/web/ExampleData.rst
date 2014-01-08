.. java:import:: org.apache.commons.beanutils PropertyUtils

.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.motechproject.mds.dto AdvancedSettingsDto

.. java:import:: org.motechproject.mds.dto AvailableTypeDto

.. java:import:: org.motechproject.mds.dto BrowsingSettingsDto

.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: org.motechproject.mds.dto FieldBasicDto

.. java:import:: org.motechproject.mds.dto FieldDto

.. java:import:: org.motechproject.mds.dto FieldInstanceDto

.. java:import:: org.motechproject.mds.dto FieldValidationDto

.. java:import:: org.motechproject.mds.dto MetadataDto

.. java:import:: org.motechproject.mds.dto RestOptions

.. java:import:: org.motechproject.mds.dto SettingDto

.. java:import:: org.motechproject.mds.dto TrackingDto

.. java:import:: org.motechproject.mds.dto TypeDto

.. java:import:: org.motechproject.mds.web.domain EntityRecord

.. java:import:: org.motechproject.mds.web.domain FieldRecord

.. java:import:: org.motechproject.mds.web.domain HistoryRecord

.. java:import:: java.io IOException

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util Collections

.. java:import:: java.util Comparator

.. java:import:: java.util HashMap

.. java:import:: java.util LinkedList

.. java:import:: java.util List

.. java:import:: java.util Map

ExampleData
===========

.. java:package:: org.motechproject.mds.web
   :noindex:

.. java:type:: @SuppressWarnings public class ExampleData

   The \ ``ExampleData``\  is a temporary class which contains example data for UI. In the future this class should be removed and data should come from database.

Constructors
------------
ExampleData
^^^^^^^^^^^

.. java:constructor:: public ExampleData()
   :outertype: ExampleData

Methods
-------
abandonChanges
^^^^^^^^^^^^^^

.. java:method:: public void abandonChanges(String entityId)
   :outertype: ExampleData

addEntity
^^^^^^^^^

.. java:method:: public void addEntity(EntityDto entity)
   :outertype: ExampleData

addOrUpdateField
^^^^^^^^^^^^^^^^

.. java:method:: public void addOrUpdateField(FieldDto field)
   :outertype: ExampleData

commitChanges
^^^^^^^^^^^^^

.. java:method:: public void commitChanges(String entityId)
   :outertype: ExampleData

createEntityHistoryRecords
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<HistoryRecord> createEntityHistoryRecords()
   :outertype: ExampleData

createEntityRecords
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<EntityRecord> createEntityRecords()
   :outertype: ExampleData

draft
^^^^^

.. java:method:: public void draft(String entityId, DraftData data)
   :outertype: ExampleData

findFieldByName
^^^^^^^^^^^^^^^

.. java:method:: public FieldDto findFieldByName(String entityId, String name)
   :outertype: ExampleData

getAdvanced
^^^^^^^^^^^

.. java:method:: public AdvancedSettingsDto getAdvanced(String entityId)
   :outertype: ExampleData

getAvailableType
^^^^^^^^^^^^^^^^

.. java:method:: public AvailableTypeDto getAvailableType(String typeClass)
   :outertype: ExampleData

getEntities
^^^^^^^^^^^

.. java:method:: public List<EntityDto> getEntities()
   :outertype: ExampleData

getEntity
^^^^^^^^^

.. java:method:: public EntityDto getEntity(String id)
   :outertype: ExampleData

getEntityRecordsById
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<EntityRecord> getEntityRecordsById(String entityId)
   :outertype: ExampleData

getField
^^^^^^^^

.. java:method:: public FieldDto getField(String id)
   :outertype: ExampleData

getFields
^^^^^^^^^

.. java:method:: public List<FieldDto> getFields(String entityId)
   :outertype: ExampleData

getInstanceFields
^^^^^^^^^^^^^^^^^

.. java:method:: public List<FieldInstanceDto> getInstanceFields(String instanceId)
   :outertype: ExampleData

getInstanceHistoryRecordsById
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<HistoryRecord> getInstanceHistoryRecordsById(String instanceId)
   :outertype: ExampleData

getTypes
^^^^^^^^

.. java:method:: public List<AvailableTypeDto> getTypes()
   :outertype: ExampleData

hasEntityWithName
^^^^^^^^^^^^^^^^^

.. java:method:: public boolean hasEntityWithName(String name)
   :outertype: ExampleData

removeEntity
^^^^^^^^^^^^

.. java:method:: public void removeEntity(EntityDto entity)
   :outertype: ExampleData

removeField
^^^^^^^^^^^

.. java:method:: public void removeField(String id)
   :outertype: ExampleData

