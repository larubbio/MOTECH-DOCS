.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.motechproject.mds.dto AdvancedSettingsDto

.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: org.motechproject.mds.dto FieldBasicDto

.. java:import:: org.motechproject.mds.dto FieldDto

.. java:import:: org.motechproject.mds.dto FieldValidationDto

.. java:import:: org.motechproject.mds.dto MetadataDto

.. java:import:: org.motechproject.mds.dto RestOptions

.. java:import:: org.motechproject.mds.ex EntityAlreadyExistException

.. java:import:: org.motechproject.mds.ex EntityNotFoundException

.. java:import:: org.motechproject.mds.ex EntityReadOnlyException

.. java:import:: org.motechproject.mds.web DraftData

.. java:import:: org.motechproject.mds.web ExampleData

.. java:import:: org.motechproject.mds.web SelectData

.. java:import:: org.motechproject.mds.web SelectResult

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashMap

.. java:import:: java.util LinkedList

.. java:import:: java.util List

EntityControllerTest
====================

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: public class EntityControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: EntityControllerTest

shouldAbandonChanges
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAbandonChanges() throws Exception
   :outertype: EntityControllerTest

shouldComitChanges
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldComitChanges() throws Exception
   :outertype: EntityControllerTest

shouldCreateNewEntity
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateNewEntity() throws Exception
   :outertype: EntityControllerTest

shouldDeleteEntity
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteEntity() throws Exception
   :outertype: EntityControllerTest

shouldFindFieldByName
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindFieldByName() throws Exception
   :outertype: EntityControllerTest

shouldGetAdvancedSettingsForEntity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAdvancedSettingsForEntity() throws Exception
   :outertype: EntityControllerTest

shouldGetEntityFields
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetEntityFields() throws Exception
   :outertype: EntityControllerTest

shouldNotAbandonChangesIfEntityNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAbandonChangesIfEntityNotExists() throws Exception
   :outertype: EntityControllerTest

shouldNotComitChangesIfEntityNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotComitChangesIfEntityNotExists() throws Exception
   :outertype: EntityControllerTest

shouldNotFindFieldByNameIfEntityNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotFindFieldByNameIfEntityNotExists() throws Exception
   :outertype: EntityControllerTest

shouldNotGetEntityFieldsIfEntityNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotGetEntityFieldsIfEntityNotExists() throws Exception
   :outertype: EntityControllerTest

shouldNotSaveTemporaryChangeIfEntityIsReadonly
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTemporaryChangeIfEntityIsReadonly() throws Exception
   :outertype: EntityControllerTest

shouldNotSaveTemporaryChangeIfEntityNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTemporaryChangeIfEntityNotExists() throws Exception
   :outertype: EntityControllerTest

shouldReturnEntityById
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnEntityById() throws Exception
   :outertype: EntityControllerTest

shouldReturnRecordsSortedByName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnRecordsSortedByName() throws Exception
   :outertype: EntityControllerTest

shouldSaveTemporaryChange
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveTemporaryChange() throws Exception
   :outertype: EntityControllerTest

shouldThrowExceptionIfEntityToDeleteNotExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfEntityToDeleteNotExists() throws Exception
   :outertype: EntityControllerTest

shouldThrowExceptionIfEntityToDeleteisReadonly
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfEntityToDeleteisReadonly() throws Exception
   :outertype: EntityControllerTest

shouldThrowExceptionIfNotFoundEntity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfNotFoundEntity() throws Exception
   :outertype: EntityControllerTest

shouldThrowOExceptionIfEntityWithGivenNameExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowOExceptionIfEntityWithGivenNameExists() throws Exception
   :outertype: EntityControllerTest

