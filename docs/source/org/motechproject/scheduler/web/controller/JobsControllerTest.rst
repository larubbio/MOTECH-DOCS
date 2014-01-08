.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.web.domain JobsRecords

.. java:import:: org.motechproject.scheduler.web.domain JobsGridSettings

.. java:import:: java.util ArrayList

.. java:import:: java.util List

JobsControllerTest
==================

.. java:package:: org.motechproject.scheduler.web.controller
   :noindex:

.. java:type:: public class JobsControllerTest

Fields
------
jobsController
^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  JobsController jobsController
   :outertype: JobsControllerTest

motechSchedulerService
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  MotechSchedulerService motechSchedulerService
   :outertype: JobsControllerTest

testJobBasicInfo1
^^^^^^^^^^^^^^^^^

.. java:field::  JobBasicInfo testJobBasicInfo1
   :outertype: JobsControllerTest

testJobBasicInfo2
^^^^^^^^^^^^^^^^^

.. java:field::  JobBasicInfo testJobBasicInfo2
   :outertype: JobsControllerTest

testJobBasicInfo3
^^^^^^^^^^^^^^^^^

.. java:field::  JobBasicInfo testJobBasicInfo3
   :outertype: JobsControllerTest

testJobBasicInfo4
^^^^^^^^^^^^^^^^^

.. java:field::  JobBasicInfo testJobBasicInfo4
   :outertype: JobsControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: JobsControllerTest

shouldFilterJobsByActivity
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFilterJobsByActivity()
   :outertype: JobsControllerTest

shouldFilterJobsByStatus
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFilterJobsByStatus()
   :outertype: JobsControllerTest

shouldGetJobeDetailedInfo
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetJobeDetailedInfo()
   :outertype: JobsControllerTest

shouldGetJobsRecords
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetJobsRecords()
   :outertype: JobsControllerTest

shouldSortJobsByEndDate
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSortJobsByEndDate()
   :outertype: JobsControllerTest

shouldSortJobsByStartDate
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSortJobsByStartDate()
   :outertype: JobsControllerTest

