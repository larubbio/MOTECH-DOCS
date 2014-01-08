.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.node ObjectNode

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: org.motechproject.tasks.service TaskService

.. java:import:: org.motechproject.tasks.service TaskTriggerHandler

.. java:import:: org.motechproject.tasks.service TriggerHandler

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io ByteArrayInputStream

.. java:import:: java.io PrintWriter

.. java:import:: java.io StringWriter

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

TaskControllerTest
==================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: public class TaskControllerTest

Fields
------
controller
^^^^^^^^^^

.. java:field::  TaskController controller
   :outertype: TaskControllerTest

eventListenerRegistryService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  EventListenerRegistryService eventListenerRegistryService
   :outertype: TaskControllerTest

file
^^^^

.. java:field:: @Mock  MultipartFile file
   :outertype: TaskControllerTest

messageService
^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskActivityService messageService
   :outertype: TaskControllerTest

printWriter
^^^^^^^^^^^

.. java:field:: @Mock  PrintWriter printWriter
   :outertype: TaskControllerTest

response
^^^^^^^^

.. java:field:: @Mock  HttpServletResponse response
   :outertype: TaskControllerTest

taskService
^^^^^^^^^^^

.. java:field:: @Mock  TaskService taskService
   :outertype: TaskControllerTest

triggerHandler
^^^^^^^^^^^^^^

.. java:field::  TriggerHandler triggerHandler
   :outertype: TaskControllerTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: TaskControllerTest

shouldDeleteTaskAndHistory
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteTaskAndHistory()
   :outertype: TaskControllerTest

shouldExportTask
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldExportTask() throws Exception
   :outertype: TaskControllerTest

shouldGetAllTasks
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllTasks()
   :outertype: TaskControllerTest

shouldGetTaskWithId
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetTaskWithId()
   :outertype: TaskControllerTest

shouldImportTask
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldImportTask() throws Exception
   :outertype: TaskControllerTest

shouldNotSaveNewTask
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveNewTask()
   :outertype: TaskControllerTest

shouldSaveExistingTask
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveExistingTask()
   :outertype: TaskControllerTest

shouldSaveTaskAndRegisterHandlerForNewTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveTaskAndRegisterHandlerForNewTrigger()
   :outertype: TaskControllerTest

