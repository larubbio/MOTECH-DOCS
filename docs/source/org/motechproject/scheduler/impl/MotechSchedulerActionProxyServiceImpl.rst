.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.scheduler MotechSchedulerActionProxyService

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain DayOfWeekSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

MotechSchedulerActionProxyServiceImpl
=====================================

.. java:package:: org.motechproject.scheduler.impl
   :noindex:

.. java:type:: @Service public class MotechSchedulerActionProxyServiceImpl implements MotechSchedulerActionProxyService

Constructors
------------
MotechSchedulerActionProxyServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechSchedulerActionProxyServiceImpl(MotechSchedulerService schedulerService)
   :outertype: MotechSchedulerActionProxyServiceImpl

Methods
-------
scheduleCronJob
^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleCronJob(String subject, Map<Object, Object> parameters, String cronExpression, DateTime startTime, DateTime endTime, Boolean ignorePastFiresAtStart)
   :outertype: MotechSchedulerActionProxyServiceImpl

scheduleDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleDayOfWeekJob(String subject, Map<Object, Object> parameters, DateTime start, DateTime end, List<Object> days, DateTime time, Boolean ignorePastFiresAtStart)
   :outertype: MotechSchedulerActionProxyServiceImpl

scheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleRepeatingJob(String subject, Map<Object, Object> parameters, DateTime startTime, DateTime endTime, Integer repeatCount, Long repeatIntervalInMilliSeconds, Boolean ignorePastFiresAtStart, Boolean useOriginalFireTimeAfterMisfire)
   :outertype: MotechSchedulerActionProxyServiceImpl

scheduleRunOnceJob
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleRunOnceJob(String subject, Map<Object, Object> parameters, DateTime startDate)
   :outertype: MotechSchedulerActionProxyServiceImpl

unscheduleJobs
^^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleJobs(String subject)
   :outertype: MotechSchedulerActionProxyServiceImpl

