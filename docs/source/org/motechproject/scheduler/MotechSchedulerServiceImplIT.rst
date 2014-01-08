.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeConstants

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain DayOfWeekSchedulableJob

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.domain JobDetailedInfo

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.motechproject.scheduler.exception MotechSchedulerException

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.quartz JobKey

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz Trigger

.. java:import:: org.quartz.impl.matchers GroupMatcher

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

MotechSchedulerServiceImplIT
============================

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MotechSchedulerServiceImplIT

Fields
------
eventListenerRegistryService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  EventListenerRegistryService eventListenerRegistryService
   :outertype: MotechSchedulerServiceImplIT

motechSchedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  MotechSchedulerFactoryBean motechSchedulerFactoryBean
   :outertype: MotechSchedulerServiceImplIT

scheduler
^^^^^^^^^

.. java:field::  Scheduler scheduler
   :outertype: MotechSchedulerServiceImplIT

schedulerService
^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  MotechSchedulerService schedulerService
   :outertype: MotechSchedulerServiceImplIT

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: MotechSchedulerServiceImplIT

shouldGetJobTimes
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetJobTimes()
   :outertype: MotechSchedulerServiceImplIT

shouldGetScheduledJobDetailedInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetScheduledJobDetailedInfo()
   :outertype: MotechSchedulerServiceImplIT

shouldGetScheduledJobsBasicInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetScheduledJobsBasicInfo() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldIgnoreFiresInPastWhenSchedulingCronJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldIgnoreFiresInPastWhenSchedulingCronJob() throws InterruptedException, SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldNotIgnoreFiresInPastWhenSchedulingCronJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotIgnoreFiresInPastWhenSchedulingCronJob() throws InterruptedException, SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldNotScheduleRunOnceJobInThePast
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotScheduleRunOnceJobInThePast() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldRescheduleCronJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRescheduleCronJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldRescheduleCronJobWithNewSchedule
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRescheduleCronJobWithNewSchedule() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleCronJob
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleCronJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleDayOfWeekJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleInterveningDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleInterveningDayOfWeekJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleInterveningRepeatJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleInterveningRepeatJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleInterveningRepeatJobWithoutEndDate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleInterveningRepeatJobWithoutEndDate() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleRepeatJobBoundByCount
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleRepeatJobBoundByCount() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleRepeatJobBoundByEndDate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleRepeatJobBoundByEndDate() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldScheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleRunOnceJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForInvalidCronExpression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForInvalidCronExpression() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForInvalidCronExpressionWhenreschedulingJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForInvalidCronExpressionWhenreschedulingJob() throws Exception
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForNullCronJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForNullCronJob() throws Exception
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForNullMotechEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForNullMotechEvent() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForNullRepeatJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForNullRepeatJob() throws Exception
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForNullRunOneceJob
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForNullRunOneceJob() throws Exception
   :outertype: MotechSchedulerServiceImplIT

shouldThrowExceptionForNullStartTime
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionForNullStartTime() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldUnscheduleAllJobsWithAGivenJobIdPrefix
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUnscheduleAllJobsWithAGivenJobIdPrefix() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

shouldUnscheduleJob
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUnscheduleJob() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown() throws SchedulerException
   :outertype: MotechSchedulerServiceImplIT

