.. java:import:: org.joda.time DateTime

.. java:import:: java.util List

.. java:import:: java.util Map

MotechSchedulerActionProxyService
=================================

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: public interface MotechSchedulerActionProxyService

Methods
-------
scheduleCronJob
^^^^^^^^^^^^^^^

.. java:method::  void scheduleCronJob(String subject, Map<Object, Object> parameters, String cronExpression, DateTime startTime, DateTime endTime, Boolean ignorePastFiresAtStart)
   :outertype: MotechSchedulerActionProxyService

scheduleDayOfWeekJob
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleDayOfWeekJob(String subject, Map<Object, Object> parameters, DateTime start, DateTime end, List<Object> days, DateTime time, Boolean ignorePastFiresAtStart)
   :outertype: MotechSchedulerActionProxyService

scheduleRepeatingJob
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleRepeatingJob(String subject, Map<Object, Object> parameters, DateTime startTime, DateTime endTime, Integer repeatCount, Long repeatIntervalInMilliSeconds, Boolean ignorePastFiresAtStart, Boolean useOriginalFireTimeAfterMisfire)
   :outertype: MotechSchedulerActionProxyService

scheduleRunOnceJob
^^^^^^^^^^^^^^^^^^

.. java:method::  void scheduleRunOnceJob(String subject, Map<Object, Object> parameters, DateTime startDate)
   :outertype: MotechSchedulerActionProxyService

unscheduleJobs
^^^^^^^^^^^^^^

.. java:method::  void unscheduleJobs(String subject)
   :outertype: MotechSchedulerActionProxyService

