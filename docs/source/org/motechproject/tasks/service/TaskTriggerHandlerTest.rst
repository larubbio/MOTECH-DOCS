.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time LocalDate

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.commons.api DataProvider

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.event.listener.annotations MotechListenerEventProxy

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.domain TaskConfig

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util Collections

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

TaskTriggerHandlerTest
======================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public class TaskTriggerHandlerTest

Fields
------
actionEvent
^^^^^^^^^^^

.. java:field::  ActionEvent actionEvent
   :outertype: TaskTriggerHandlerTest

bundleContext
^^^^^^^^^^^^^

.. java:field:: @Mock  BundleContext bundleContext
   :outertype: TaskTriggerHandlerTest

dataProvider
^^^^^^^^^^^^

.. java:field:: @Mock  DataProvider dataProvider
   :outertype: TaskTriggerHandlerTest

eventRelay
^^^^^^^^^^

.. java:field:: @Mock  EventRelay eventRelay
   :outertype: TaskTriggerHandlerTest

exception
^^^^^^^^^

.. java:field:: @Mock  Exception exception
   :outertype: TaskTriggerHandlerTest

handler
^^^^^^^

.. java:field::  TaskTriggerHandler handler
   :outertype: TaskTriggerHandlerTest

registryService
^^^^^^^^^^^^^^^

.. java:field:: @Mock  EventListenerRegistryService registryService
   :outertype: TaskTriggerHandlerTest

serviceReference
^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ServiceReference serviceReference
   :outertype: TaskTriggerHandlerTest

settingsFacade
^^^^^^^^^^^^^^

.. java:field:: @Mock  SettingsFacade settingsFacade
   :outertype: TaskTriggerHandlerTest

task
^^^^

.. java:field::  Task task
   :outertype: TaskTriggerHandlerTest

taskActivities
^^^^^^^^^^^^^^

.. java:field::  List<TaskActivity> taskActivities
   :outertype: TaskTriggerHandlerTest

taskActivityService
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskActivityService taskActivityService
   :outertype: TaskTriggerHandlerTest

taskService
^^^^^^^^^^^

.. java:field:: @Mock  TaskService taskService
   :outertype: TaskTriggerHandlerTest

tasks
^^^^^

.. java:field::  List<Task> tasks
   :outertype: TaskTriggerHandlerTest

triggerEvent
^^^^^^^^^^^^

.. java:field::  TriggerEvent triggerEvent
   :outertype: TaskTriggerHandlerTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldCaptureUnrecognizedError
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCaptureUnrecognizedError() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldDisableTaskWhenActionDoesNotFindDataSource_WithFailIfDataNotFoundSelected
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDisableTaskWhenActionDoesNotFindDataSource_WithFailIfDataNotFoundSelected() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldDisableTaskWhenFilterDoesNotFindDataSource_WithFailIfDataNotFoundSelected
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDisableTaskWhenFilterDoesNotFindDataSource_WithFailIfDataNotFoundSelected() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldDisableTaskWhenNumberPossibleErrorsIsExceeded
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDisableTaskWhenNumberPossibleErrorsIsExceeded() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldExecuteServiceMethod
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldExecuteServiceMethod() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldExecuteTwoActions
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldExecuteTwoActions() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldGetWarningWhenManipulationHaveMistake
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetWarningWhenManipulationHaveMistake() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldHandleFormatManipulation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldHandleFormatManipulation() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotDisableTaskWhenActionDoesNotFindDataSource_WithFailIfDataNotFoundNotSelected
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotDisableTaskWhenActionDoesNotFindDataSource_WithFailIfDataNotFoundNotSelected() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotDisableTaskWhenFilterDoesNotFindDataSource_WithFailIfDataNotFoundNotSelected
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotDisableTaskWhenFilterDoesNotFindDataSource_WithFailIfDataNotFoundNotSelected() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotExecuteServiceMethodIfBundleContextIsNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotExecuteServiceMethodIfBundleContextIsNull() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotExecuteServiceMethodIfServiceReferenceIsNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotExecuteServiceMethodIfServiceReferenceIsNull() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotPassFiltersCriteria
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotPassFiltersCriteria() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotRegisterHandler
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterHandler()
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToBoolean
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToBoolean() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToDate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToDate() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToDouble
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToDouble() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToInteger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToInteger() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToLong
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToLong() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfActionEventParameterCanNotBeConvertedToTime
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfActionEventParameterCanNotBeConvertedToTime() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfDataProviderNotFoundObject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfDataProviderNotFoundObject() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfDataProviderObjectNotContainsField
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfDataProviderObjectNotContainsField() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfDataProvidersListIsEmpty
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfDataProvidersListIsEmpty() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfDataProvidersListIsNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfDataProvidersListIsNull() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventIfDateFormatInManipulationIsNotValid
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventIfDateFormatInManipulationIsNotValid() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventWhenActionEventParameterHasNotValue
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventWhenActionEventParameterHasNotValue() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventWhenActionEventParameterNotContainValue
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventWhenActionEventParameterNotContainValue() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventWhenActionNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventWhenActionNotFound() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventWhenTaskIsDisabled
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventWhenTaskIsDisabled() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldNotSendEventWhenTasksChannelIsDeregistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSendEventWhenTasksChannelIsDeregistered() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldPassFiltersCriteria
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPassFiltersCriteria() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldRegisterHandlerForSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterHandlerForSubject()
   :outertype: TaskTriggerHandlerTest

shouldRegisterHandlerOneTimeForSameSubjects
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterHandlerOneTimeForSameSubjects()
   :outertype: TaskTriggerHandlerTest

shouldSendEventAndConverseDateWithAndWithoutManipulation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventAndConverseDateWithAndWithoutManipulation() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldSendEventForGivenTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventForGivenTrigger() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldSendEventIfAdditionalDataNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventIfAdditionalDataNotFound() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldSendEventIfServiceIsNotAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventIfServiceIsNotAvailable() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldThrowExceptionWhenTriggerNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenTriggerNotFound() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldThrowTaskExceptionWhenServiceMethodNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowTaskExceptionWhenServiceMethodNotFound() throws Exception
   :outertype: TaskTriggerHandlerTest

shouldThrowTaskExceptionWhenServiceMethodThrowException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowTaskExceptionWhenServiceMethodThrowException() throws Exception
   :outertype: TaskTriggerHandlerTest

