.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util List

TaskDataProviderController
==========================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @Controller public class TaskDataProviderController

Constructors
------------
TaskDataProviderController
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskDataProviderController(TaskDataProviderService taskDataProviderService)
   :outertype: TaskDataProviderController

Methods
-------
getAllDataProviders
^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<TaskDataProvider> getAllDataProviders()
   :outertype: TaskDataProviderController

