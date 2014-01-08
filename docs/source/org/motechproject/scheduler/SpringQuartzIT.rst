.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.motechproject.scheduler.impl MotechScheduledJob

.. java:import:: org.quartz JobDetail

.. java:import:: org.quartz JobKey

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz SimpleTrigger

.. java:import:: org.quartz TriggerKey

.. java:import:: org.quartz.impl.matchers GroupMatcher

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util List

.. java:import:: java.util UUID

SpringQuartzIT
==============

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class SpringQuartzIT

Fields
------
groupName
^^^^^^^^^

.. java:field::  String groupName
   :outertype: SpringQuartzIT

Methods
-------
scheduleUnscheduleTest
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void scheduleUnscheduleTest() throws SchedulerException
   :outertype: SpringQuartzIT

shouldWaitForJobsToCompleteBeforeShutdown
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldWaitForJobsToCompleteBeforeShutdown()
   :outertype: SpringQuartzIT

