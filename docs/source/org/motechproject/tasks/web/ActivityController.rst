.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.util List

ActivityController
==================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @Controller public class ActivityController

Constructors
------------
ActivityController
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ActivityController(TaskActivityService activityService)
   :outertype: ActivityController

Methods
-------
deleteActivitiesForTask
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void deleteActivitiesForTask(String taskId)
   :outertype: ActivityController

getAllActivities
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<TaskActivity> getAllActivities()
   :outertype: ActivityController

getTaskActivities
^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<TaskActivity> getTaskActivities(String taskId)
   :outertype: ActivityController

