.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain DayOfWeekSchedulableJob

.. java:import:: org.motechproject.scheduler.domain JobId

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.domain JobDetailedInfo

.. java:import:: java.util Date

.. java:import:: java.util List

MotechSchedulerService
======================

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: public interface MotechSchedulerService

   \ingroup scheduler Motech Scheduler Service Interface provides methods to schedule reschedule and unschedule a job Set a global policy that determines trigger fire behaviour for misfired triggers. For details see quartz documentations for misfire policy do_nothing -> @see CronTrigger.MISFIRE_INSTRUCTION_DO_NOTHING fire_once_now -> @see CronTrigger.MISFIRE_INSTRUCTION_FIRE_ONCE_NOW ignore -> @see CronTrigger.MISFIRE_INSTRUCTION_IGNORE_MISFIRE_POLICY fire_now -> @see SimpleTrigger.MISFIRE_INSTRUCTION_FIRE_NOW ignore -> @see SimpleTrigger.MISFIRE_INSTRUCTION_IGNORE_MISFIRE_POLICY reschedule_next_with_existing_count -> @see SimpleTrigger.MISFIRE_INSTRUCTION_RESCHEDULE_NEXT_WITH_EXISTING_COUNT reschedule_next_with_remaining_count -> @see SimpleTrigger.MISFIRE_INSTRUCTION_RESCHEDULE_NEXT_WITH_REMAINING_COUNT reschedule_now_with_existing_count -> @see SimpleTrigger.MISFIRE_INSTRUCTION_RESCHEDULE_NOW_WITH_EXISTING_REPEAT_COUNT reschedule_now_with_remaining_count -> @see SimpleTrigger.MISFIRE_INSTRUCTION_RESCHEDULE_NOW_WITH_REMAINING_REPEAT_COUNT Scheduler can use couchdb for its job store. To enable set the following properties org.quartz.jobStore.class = org.motechproject.quartz.CouchDbStore org.quartz.jobStore.dbNameGenerator = org.motechproject.scheduler.impl.MultiTenantQuartzDatabaseName # provides database names for the jobstore, used in a multi-tenant environment to have separate databases for each tenant; leave blank to use a single database org.quartz.jobStore.properties =  # a couchdb.properties file understood by ektorp to specify the database environment

   :author: Igor (iopushnyev@2paths.com) Date: 16/02/11

Fields
------
JOB_ID_KEY
^^^^^^^^^^

.. java:field::  String JOB_ID_KEY
   :outertype: MotechSchedulerService

Methods
-------
getScheduledJobDetailedInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  JobDetailedInfo getScheduledJobDetailedInfo(JobBasicInfo jobBasicInfo)
   :outertype: MotechSchedulerService

getScheduledJobTimings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<Date> getScheduledJobTimings(String subject, String externalJobId, Date startDate, Date endDate)
   :outertype: MotechSchedulerService

getScheduledJobTimingsWithPrefix
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<Date> getScheduledJobTimingsWithPrefix(String subject, String externalJobIdPrefix, Date startDate, Date endDate)
   :outertype: MotechSchedulerService

getScheduledJobsBasicInfo
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<JobBasicInfo> getScheduledJobsBasicInfo()
   :outertype: MotechSchedulerService

rescheduleJob
^^^^^^^^^^^^^

.. java:method::  void rescheduleJob(String subject, String externalId, String cronExpression)
   :outertype: MotechSchedulerService

   Reschedules a job with the given job ID to be fired according to the given Cron Expression Previous version of the configured Motech Scheduled Even that will be created when the job is fired remains us it was

   :param subject:
   :param externalId:
   :param cronExpression:

safeScheduleJob
^^^^^^^^^^^^^^^

.. java:method::  void safeScheduleJob(CronSchedulableJob cronSchedulableJob)
   :outertype: MotechSchedulerService

   Same as scheduleJob, except that it would update existing job if one exists instead of creating a new one

   :param cronSchedulableJob:

safeScheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void safeScheduleRepeatingJob(RepeatingSchedulableJob repeatingSchedulableJob)
   :outertype: MotechSchedulerService

   Same as safeScheduleRepeatingJob with intervening = true

   :param repeatingSchedulableJob:

safeScheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void safeScheduleRunOnceJob(RunOnceSchedulableJob schedulableJob)
   :outertype: MotechSchedulerService

   Same as scheduleRunOnceJob, except that it would update existing job if one exists instead of creating a new one

   :param schedulableJob:

safeUnscheduleAllJobs
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void safeUnscheduleAllJobs(String jobIdPrefix)
   :outertype: MotechSchedulerService

safeUnscheduleJob
^^^^^^^^^^^^^^^^^

.. java:method::  void safeUnscheduleJob(String subject, String externalId)
   :outertype: MotechSchedulerService

   Same as unscheduleJob except that it would not throw an exception if the job doesn't exist

   :param subject:
   :param externalId:

safeUnscheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void safeUnscheduleRepeatingJob(String subject, String externalId)
   :outertype: MotechSchedulerService

   Same as unscheduleRepeatingJob except that it would not throw an exception if the job doesn't exist

   :param subject:
   :param externalId:

safeUnscheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void safeUnscheduleRunOnceJob(String subject, String externalId)
   :outertype: MotechSchedulerService

   Same as unscheduleRunOnceJob except that it would not throw an exception if the job doesn't exist

   :param subject:
   :param externalId:

scheduleDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleDayOfWeekJob(DayOfWeekSchedulableJob dayOfWeekSchedulableJob)
   :outertype: MotechSchedulerService

   Same as safeScheduleDayOfWeekJob with intervening = true

   :param dayOfWeekSchedulableJob:

scheduleJob
^^^^^^^^^^^

.. java:method::  void scheduleJob(CronSchedulableJob cronSchedulableJob)
   :outertype: MotechSchedulerService

   Schedules the given schedulable job. The Job ID by which the job will be referencing in the future should be provided in an Instance of MotechEvent in SchedulableJob (see MotechEvent.jobId) If a job with the same job ID as the given exists, this job will be unscheduled and the given schedulable job will be scheduled

   :param cronSchedulableJob:

scheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleRepeatingJob(RepeatingSchedulableJob repeatingSchedulableJob)
   :outertype: MotechSchedulerService

   Schedules the given schedulable job. The Job ID by which the job will be referencing in the future should be provided in an Instance of MotechEvent in SchedulableJob (see MotechEvent.jobId) If a job with the same job ID as the given exists, this job will be unscheduled and the given schedulable job will be scheduled

   :param repeatingSchedulableJob:

scheduleRunOnceJob
^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleRunOnceJob(RunOnceSchedulableJob schedulableJob)
   :outertype: MotechSchedulerService

unscheduleAllJobs
^^^^^^^^^^^^^^^^^

.. java:method::  void unscheduleAllJobs(String jobIdPrefix)
   :outertype: MotechSchedulerService

unscheduleJob
^^^^^^^^^^^^^

.. java:method::  void unscheduleJob(String subject, String externalId)
   :outertype: MotechSchedulerService

   Unschedules a job with the given job ID

   :param subject: : String representing domain operation eg. "pill-reminder", "outbox-call" or motechEvent.getSubject()
   :param externalId: : domain specific id as String.

unscheduleJob
^^^^^^^^^^^^^

.. java:method::  void unscheduleJob(JobId job)
   :outertype: MotechSchedulerService

unscheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void unscheduleRepeatingJob(String subject, String externalId)
   :outertype: MotechSchedulerService

unscheduleRunOnceJob
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void unscheduleRunOnceJob(String subject, String externalId)
   :outertype: MotechSchedulerService

   Unschedules a run once job with the given job ID

   :param subject: : String representing domain operation eg. "pill-reminder", "outbox-call" or motechEvent.getSubject()
   :param externalId: : domain specific id as String.

updateScheduledJob
^^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated  void updateScheduledJob(MotechEvent motechEvent)
   :outertype: MotechSchedulerService

   Updates MotechEvent data of the job defined by jobIb in the given instance of that class

   :param motechEvent:

