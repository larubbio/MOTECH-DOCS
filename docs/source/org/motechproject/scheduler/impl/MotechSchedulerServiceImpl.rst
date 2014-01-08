.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.log4j Logger

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time LocalDate

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain CronJobId

.. java:import:: org.motechproject.scheduler.domain DayOfWeekSchedulableJob

.. java:import:: org.motechproject.scheduler.domain EventInfo

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.domain JobDetailedInfo

.. java:import:: org.motechproject.scheduler.domain JobId

.. java:import:: org.motechproject.scheduler.domain RepeatingJobId

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RunOnceJobId

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.motechproject.scheduler.exception MotechSchedulerException

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz CronScheduleBuilder

.. java:import:: org.quartz CronTrigger

.. java:import:: org.quartz SimpleTrigger

.. java:import:: org.quartz JobDetail

.. java:import:: org.quartz JobDataMap

.. java:import:: org.quartz Trigger

.. java:import:: org.quartz ScheduleBuilder

.. java:import:: org.quartz SimpleScheduleBuilder

.. java:import:: org.quartz CalendarIntervalScheduleBuilder

.. java:import:: org.quartz TriggerUtils

.. java:import:: org.quartz TriggerKey

.. java:import:: org.quartz JobKey

.. java:import:: org.quartz CalendarIntervalTrigger

.. java:import:: org.quartz.impl.calendar BaseCalendar

.. java:import:: org.quartz.impl.matchers GroupMatcher

.. java:import:: org.quartz.impl.triggers CronTriggerImpl

.. java:import:: org.quartz.spi OperableTrigger

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util Map

.. java:import:: java.util List

.. java:import:: java.util Date

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

MotechSchedulerServiceImpl
==========================

.. java:package:: org.motechproject.scheduler.impl
   :noindex:

.. java:type:: @Service public class MotechSchedulerServiceImpl implements MotechSchedulerService

   Motech Scheduler Service implementation

Fields
------
JOB_GROUP_NAME
^^^^^^^^^^^^^^

.. java:field:: public static final String JOB_GROUP_NAME
   :outertype: MotechSchedulerServiceImpl

Constructors
------------
MotechSchedulerServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechSchedulerServiceImpl(MotechSchedulerFactoryBean motechSchedulerFactoryBean, SettingsFacade schedulerSettings)
   :outertype: MotechSchedulerServiceImpl

Methods
-------
assertArgumentNotNull
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void assertArgumentNotNull(String objectName, Object object)
   :outertype: MotechSchedulerServiceImpl

getScheduledJobDetailedInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public JobDetailedInfo getScheduledJobDetailedInfo(JobBasicInfo jobBasicInfo)
   :outertype: MotechSchedulerServiceImpl

getScheduledJobTimings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<Date> getScheduledJobTimings(String subject, String externalJobId, Date startDate, Date endDate)
   :outertype: MotechSchedulerServiceImpl

getScheduledJobTimingsWithPrefix
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<Date> getScheduledJobTimingsWithPrefix(String subject, String externalJobIdPrefix, Date startDate, Date endDate)
   :outertype: MotechSchedulerServiceImpl

getScheduledJobsBasicInfo
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<JobBasicInfo> getScheduledJobsBasicInfo()
   :outertype: MotechSchedulerServiceImpl

rescheduleJob
^^^^^^^^^^^^^

.. java:method:: @Override public void rescheduleJob(String subject, String externalId, String cronExpression)
   :outertype: MotechSchedulerServiceImpl

safeScheduleJob
^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeScheduleJob(CronSchedulableJob cronSchedulableJob)
   :outertype: MotechSchedulerServiceImpl

safeScheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeScheduleRepeatingJob(RepeatingSchedulableJob repeatingSchedulableJob)
   :outertype: MotechSchedulerServiceImpl

safeScheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void safeScheduleRunOnceJob(RunOnceSchedulableJob schedulableJob)
   :outertype: MotechSchedulerServiceImpl

safeUnscheduleAllJobs
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeUnscheduleAllJobs(String jobIdPrefix)
   :outertype: MotechSchedulerServiceImpl

safeUnscheduleJob
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeUnscheduleJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

safeUnscheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeUnscheduleRepeatingJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

safeUnscheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void safeUnscheduleRunOnceJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

scheduleDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleDayOfWeekJob(DayOfWeekSchedulableJob dayOfWeekSchedulableJob)
   :outertype: MotechSchedulerServiceImpl

scheduleJob
^^^^^^^^^^^

.. java:method:: @Override public void scheduleJob(CronSchedulableJob cronSchedulableJob)
   :outertype: MotechSchedulerServiceImpl

scheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleRepeatingJob(RepeatingSchedulableJob repeatingSchedulableJob)
   :outertype: MotechSchedulerServiceImpl

scheduleRunOnceJob
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void scheduleRunOnceJob(RunOnceSchedulableJob schedulableJob)
   :outertype: MotechSchedulerServiceImpl

unscheduleAllJobs
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleAllJobs(String jobIdPrefix)
   :outertype: MotechSchedulerServiceImpl

unscheduleJob
^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

unscheduleJob
^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleJob(JobId job)
   :outertype: MotechSchedulerServiceImpl

unscheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleRepeatingJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

unscheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void unscheduleRunOnceJob(String subject, String externalId)
   :outertype: MotechSchedulerServiceImpl

updateScheduledJob
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override @Deprecated public void updateScheduledJob(MotechEvent motechEvent)
   :outertype: MotechSchedulerServiceImpl

