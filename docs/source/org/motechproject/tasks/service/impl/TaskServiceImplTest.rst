.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.hamcrest Description

.. java:import:: org.hamcrest TypeSafeMatcher

.. java:import:: org.junit Before

.. java:import:: org.junit Rule

.. java:import:: org.junit Test

.. java:import:: org.junit.rules ExpectedException

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TaskNotFoundException

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.repository AllTasks

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

TaskServiceImplTest
===================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: public class TaskServiceImplTest

Fields
------
allTasks
^^^^^^^^

.. java:field:: @Mock  AllTasks allTasks
   :outertype: TaskServiceImplTest

channelService
^^^^^^^^^^^^^^

.. java:field:: @Mock  ChannelService channelService
   :outertype: TaskServiceImplTest

eventRelay
^^^^^^^^^^

.. java:field:: @Mock  EventRelay eventRelay
   :outertype: TaskServiceImplTest

expectedException
^^^^^^^^^^^^^^^^^

.. java:field:: @Rule public ExpectedException expectedException
   :outertype: TaskServiceImplTest

providerService
^^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskDataProviderService providerService
   :outertype: TaskServiceImplTest

taskService
^^^^^^^^^^^

.. java:field::  TaskServiceImpl taskService
   :outertype: TaskServiceImplTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: TaskServiceImplTest

shouldActivateTasksAfterChannelIsRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldActivateTasksAfterChannelIsRegistered()
   :outertype: TaskServiceImplTest

shouldConvertTaskToJSON
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldConvertTaskToJSON() throws Exception
   :outertype: TaskServiceImplTest

shouldDeactivateTasksAfterChannelIsDeregistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeactivateTasksAfterChannelIsDeregistered()
   :outertype: TaskServiceImplTest

shouldDeleteTask
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteTask()
   :outertype: TaskServiceImplTest

shouldFailValidationIfTriggerChannelIsNotRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFailValidationIfTriggerChannelIsNotRegistered()
   :outertype: TaskServiceImplTest

shouldFindActionForGivenInformation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindActionForGivenInformation() throws ActionNotFoundException
   :outertype: TaskServiceImplTest

shouldFindActionForGivenTask
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindActionForGivenTask() throws ActionNotFoundException
   :outertype: TaskServiceImplTest

shouldFindTasksForGivenTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindTasksForGivenTrigger()
   :outertype: TaskServiceImplTest

shouldFindTriggerForGivenSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindTriggerForGivenSubject() throws TriggerNotFoundException
   :outertype: TaskServiceImplTest

shouldGetAllTasks
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllTasks()
   :outertype: TaskServiceImplTest

shouldGetTaskById
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetTaskById()
   :outertype: TaskServiceImplTest

shouldImportTaskAndUpdateDataSourceIDs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldImportTaskAndUpdateDataSourceIDs() throws Exception
   :outertype: TaskServiceImplTest

shouldNotFindTasksForGivenTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotFindTasksForGivenTrigger()
   :outertype: TaskServiceImplTest

shouldNotSaveTaskIfNotMatchExtraValidationConditions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTaskIfNotMatchExtraValidationConditions()
   :outertype: TaskServiceImplTest

shouldNotSaveTaskWithNameWithContainsOnlyWhitespaces
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTaskWithNameWithContainsOnlyWhitespaces()
   :outertype: TaskServiceImplTest

shouldNotSaveTaskWithoutAction
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTaskWithoutAction()
   :outertype: TaskServiceImplTest

shouldNotSaveTaskWithoutName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTaskWithoutName()
   :outertype: TaskServiceImplTest

shouldNotSaveTaskWithoutTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveTaskWithoutTrigger()
   :outertype: TaskServiceImplTest

shouldNotUpdateTaskIfItDoesNotHaveAnyValidationErrors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotUpdateTaskIfItDoesNotHaveAnyValidationErrors()
   :outertype: TaskServiceImplTest

shouldNotValidateTasksAfterChannelUpdateIfDataSourceDoesNotExistForGivenProvider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotValidateTasksAfterChannelUpdateIfDataSourceDoesNotExistForGivenProvider()
   :outertype: TaskServiceImplTest

shouldRemoveValidationErrorAndUpdateTaskOnlyIfItHasAnyValidationErrors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveValidationErrorAndUpdateTaskOnlyIfItHasAnyValidationErrors()
   :outertype: TaskServiceImplTest

shouldSaveTask
^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveTask()
   :outertype: TaskServiceImplTest

shouldSaveTaskWithEmptyActionInputFields
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveTaskWithEmptyActionInputFields()
   :outertype: TaskServiceImplTest

shouldThrowActionNotFoundException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowActionNotFoundException() throws ActionNotFoundException
   :outertype: TaskServiceImplTest

shouldThrowActionNotFoundExceptionWhenChannelContainsEmptyActionList
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowActionNotFoundExceptionWhenChannelContainsEmptyActionList() throws ActionNotFoundException
   :outertype: TaskServiceImplTest

shouldThrowActionNotFoundExceptionWhenChannelNotContainsActions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowActionNotFoundExceptionWhenChannelNotContainsActions() throws ActionNotFoundException
   :outertype: TaskServiceImplTest

shouldThrowExceptionDuringDeletionIfTaskNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionDuringDeletionIfTaskNotFound()
   :outertype: TaskServiceImplTest

shouldThrowExceptionDuringExportingIfTaskNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionDuringExportingIfTaskNotFound()
   :outertype: TaskServiceImplTest

shouldThrowTriggerNotFoundException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowTriggerNotFoundException() throws TriggerNotFoundException
   :outertype: TaskServiceImplTest

shouldThrowTriggerNotFoundExceptionWhenChannelContainsEmptyTriggerList
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowTriggerNotFoundExceptionWhenChannelContainsEmptyTriggerList() throws TriggerNotFoundException
   :outertype: TaskServiceImplTest

shouldThrowTriggerNotFoundExceptionWhenChannelListIsEmpty
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowTriggerNotFoundExceptionWhenChannelListIsEmpty() throws TriggerNotFoundException
   :outertype: TaskServiceImplTest

shouldValidateTasksAfterChannelUpdateForInvalidActions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateTasksAfterChannelUpdateForInvalidActions()
   :outertype: TaskServiceImplTest

shouldValidateTasksAfterChannelUpdateForInvalidTaskDataProviders
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateTasksAfterChannelUpdateForInvalidTaskDataProviders()
   :outertype: TaskServiceImplTest

shouldValidateTasksAfterChannelUpdateForValidTaskDataProviders
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateTasksAfterChannelUpdateForValidTaskDataProviders()
   :outertype: TaskServiceImplTest

shouldValidateTasksAfterChannelUpdateForValidTriggers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateTasksAfterChannelUpdateForValidTriggers()
   :outertype: TaskServiceImplTest

shouldValidateTasksOfDependentModulesAfterChannelUpdateForInvalidTriggers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateTasksOfDependentModulesAfterChannelUpdateForInvalidTriggers()
   :outertype: TaskServiceImplTest

