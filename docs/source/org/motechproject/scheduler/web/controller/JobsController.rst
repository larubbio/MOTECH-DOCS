.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.domain JobDetailedInfo

.. java:import:: org.motechproject.scheduler.domain JobBasicInfoComparator

.. java:import:: org.motechproject.scheduler.web.domain JobsRecords

.. java:import:: org.motechproject.scheduler.web.domain JobsGridSettings

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util List

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

JobsController
==============

.. java:package:: org.motechproject.scheduler.web.controller
   :noindex:

.. java:type:: @Controller public class JobsController

   JobsController is the Spring Framework Controller, its used by view layer for getting information about scheduled jobs and about event associated with given Job. The methods of controller return JobsRecords class for jobs data and JobDetailedInfo class for event data. The internal methods of this class performs filtering and sorting of jobs information. The class also stores the most recent JobsRecords for information which job event data should be returned.

Methods
-------
retrieveJobDetailedInfo
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public JobDetailedInfo retrieveJobDetailedInfo(int jobid)
   :outertype: JobsController

retrieveJobInfo
^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public JobsRecords retrieveJobInfo(JobsGridSettings jobsGridSettings)
   :outertype: JobsController

