.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.io Serializable

.. java:import:: java.util Date

.. java:import:: java.util Objects

CronSchedulableJob
==================

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public class CronSchedulableJob implements Serializable

   Schedulable Job - a data carrier class for a scheduled job that can be fired unlimited number of times as specified with the cron expression

   :author: Igor (iopushnyev@2paths.com) Date: 16/02/11 Time: 1:43 PM

Constructors
------------
CronSchedulableJob
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronSchedulableJob(MotechEvent motechEvent, String cronExpression, Date startTime, Date endTime)
   :outertype: CronSchedulableJob

CronSchedulableJob
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronSchedulableJob(MotechEvent motechEvent, String cronExpression)
   :outertype: CronSchedulableJob

CronSchedulableJob
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CronSchedulableJob(MotechEvent motechEvent, String cronExpression, Date startTime, Date endTime, boolean ignorePastFiresAtStart)
   :outertype: CronSchedulableJob

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: CronSchedulableJob

getCronExpression
^^^^^^^^^^^^^^^^^

.. java:method:: public String getCronExpression()
   :outertype: CronSchedulableJob

getEndTime
^^^^^^^^^^

.. java:method:: public Date getEndTime()
   :outertype: CronSchedulableJob

getMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public MotechEvent getMotechEvent()
   :outertype: CronSchedulableJob

getStartTime
^^^^^^^^^^^^

.. java:method:: public Date getStartTime()
   :outertype: CronSchedulableJob

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: CronSchedulableJob

isIgnorePastFiresAtStart
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isIgnorePastFiresAtStart()
   :outertype: CronSchedulableJob

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: CronSchedulableJob

