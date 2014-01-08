.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.log4j Logger

.. java:import:: org.codehaus.jackson JsonFactory

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.type TypeReference

.. java:import:: org.motechproject.commons.api CsvConverter

.. java:import:: org.motechproject.mds.dto AdvancedSettingsDto

.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: org.motechproject.mds.dto FieldDto

.. java:import:: org.motechproject.mds.ex EntityAlreadyExistException

.. java:import:: org.motechproject.mds.ex EntityNotFoundException

.. java:import:: org.motechproject.mds.ex EntityReadOnlyException

.. java:import:: org.motechproject.mds.web DraftData

.. java:import:: org.motechproject.mds.web SelectData

.. java:import:: org.motechproject.mds.web SelectResult

.. java:import:: org.motechproject.mds.web.comparator EntityNameComparator

.. java:import:: org.motechproject.mds.web.comparator EntityRecordComparator

.. java:import:: org.motechproject.mds.web.domain EntityRecord

.. java:import:: org.motechproject.mds.web.domain FieldRecord

.. java:import:: org.motechproject.mds.web.domain GridSettings

.. java:import:: org.motechproject.mds.web.domain Records

.. java:import:: org.motechproject.mds.web.matcher EntityMatcher

.. java:import:: org.motechproject.mds.web.matcher WIPEntityMatcher

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.net URLDecoder

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util HashMap

.. java:import:: java.util Iterator

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

EntityController
================

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: @Controller public class EntityController extends MdsController

   The \ ``EntityController``\  is the Spring Framework Controller used by view layer for executing certain actions on entities.

Methods
-------
abandonChanges
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void abandonChanges(String entityId)
   :outertype: EntityController

commitChanges
^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void commitChanges(String entityId)
   :outertype: EntityController

deleteEntity
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public void deleteEntity(String entityId)
   :outertype: EntityController

draft
^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void draft(String entityId, DraftData data)
   :outertype: EntityController

exportEntityInstances
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping public void exportEntityInstances(String entityId, HttpServletResponse response) throws IOException
   :outertype: EntityController

getAdvanced
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public AdvancedSettingsDto getAdvanced(String entityId)
   :outertype: EntityController

getAllEntities
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<EntityDto> getAllEntities()
   :outertype: EntityController

getEntities
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public SelectResult<EntityDto> getEntities(SelectData data)
   :outertype: EntityController

getEntitiesByModule
^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Map<String, List<String>> getEntitiesByModule()
   :outertype: EntityController

getEntity
^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public EntityDto getEntity(String entityId)
   :outertype: EntityController

getEntityByModuleAndEntityName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public EntityDto getEntityByModuleAndEntityName(String module, String entityName)
   :outertype: EntityController

getFieldByName
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public FieldDto getFieldByName(String entityId, String name)
   :outertype: EntityController

getFields
^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<FieldDto> getFields(String entityId)
   :outertype: EntityController

getInstance
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<FieldRecord> getInstance(String entityId, String instanceId)
   :outertype: EntityController

getInstances
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Records<EntityRecord> getInstances(String entityId, String url, GridSettings settings)
   :outertype: EntityController

getWorkInProgressEntities
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<EntityDto> getWorkInProgressEntities()
   :outertype: EntityController

saveEntity
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public EntityDto saveEntity(EntityDto entity)
   :outertype: EntityController

