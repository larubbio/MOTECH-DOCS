.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: org.motechproject.tasks.service TaskService

.. java:import:: org.motechproject.tasks.service TriggerHandler

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io StringWriter

.. java:import:: java.util List

.. java:import:: java.util Set

TaskController
==============

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @Controller public class TaskController

   REST API for managing tasks.

Constructors
------------
TaskController
^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskController(TaskService taskService, TaskActivityService activityService, TriggerHandler triggerHandler)
   :outertype: TaskController

Methods
-------
deleteTask
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void deleteTask(String taskId)
   :outertype: TaskController

exportTask
^^^^^^^^^^

.. java:method:: @RequestMapping public void exportTask(String taskId, HttpServletResponse response) throws IOException
   :outertype: TaskController

getAllTasks
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<Task> getAllTasks()
   :outertype: TaskController

getTask
^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Task getTask(String taskId)
   :outertype: TaskController

handleException
^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public Set<TaskError> handleException(ValidationException e) throws IOException
   :outertype: TaskController

handleException
^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleException(Exception e) throws IOException
   :outertype: TaskController

importTask
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void importTask(MultipartFile jsonFile) throws IOException
   :outertype: TaskController

save
^^^^

.. java:method:: @RequestMapping @ResponseStatus public void save(Task task)
   :outertype: TaskController

saveTask
^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void saveTask(Task task)
   :outertype: TaskController

