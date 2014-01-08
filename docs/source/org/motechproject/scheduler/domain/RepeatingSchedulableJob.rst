.. java:import:: org.apache.commons.lang ObjectUtils

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.io Serializable

.. java:import:: java.util Date

RepeatingSchedulableJob
=======================

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public class RepeatingSchedulableJob implements Serializable

   Schedulable Job - a data carrier class for a scheduled job that can be fired set number of times

Constructors
------------
RepeatingSchedulableJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public RepeatingSchedulableJob()
   :outertype: RepeatingSchedulableJob

RepeatingSchedulableJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public RepeatingSchedulableJob(MotechEvent motechEvent, Date startTime, Date endTime, Integer repeatCount, Long repeatIntervalInMilliSeconds, boolean ignorePastFiresAtStart)
   :outertype: RepeatingSchedulableJob

RepeatingSchedulableJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public RepeatingSchedulableJob(MotechEvent motechEvent, Date startTime, Date endTime, Long repeatIntervalInMilliSeconds, boolean ignorePastFiresAtStart)
   :outertype: RepeatingSchedulableJob

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: RepeatingSchedulableJob

getEndTime
^^^^^^^^^^

.. java:method:: public Date getEndTime()
   :outertype: RepeatingSchedulableJob

getMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public MotechEvent getMotechEvent()
   :outertype: RepeatingSchedulableJob

getRepeatCount
^^^^^^^^^^^^^^

.. java:method:: public Integer getRepeatCount()
   :outertype: RepeatingSchedulableJob

getRepeatIntervalInMilliSeconds
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Long getRepeatIntervalInMilliSeconds()
   :outertype: RepeatingSchedulableJob

getStartTime
^^^^^^^^^^^^

.. java:method:: public Date getStartTime()
   :outertype: RepeatingSchedulableJob

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: RepeatingSchedulableJob

isIgnorePastFiresAtStart
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isIgnorePastFiresAtStart()
   :outertype: RepeatingSchedulableJob

isUseOriginalFireTimeAfterMisfire
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isUseOriginalFireTimeAfterMisfire()
   :outertype: RepeatingSchedulableJob

setEndTime
^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setEndTime(Date endTime)
   :outertype: RepeatingSchedulableJob

setIgnorePastFiresAtStart
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setIgnorePastFiresAtStart(boolean ignorePastFiresAtStart)
   :outertype: RepeatingSchedulableJob

   Ignore past fires when start time of job is in past.

   .. parsed-literal::

      ex : repeating job with interval of 5 unit, and current time in between fire 2 and 3 will start triggering from 3rd firetime.
       1     2     3     4
       |-----|-----|-----|
       start    ^current time

   :param ignorePastFiresAtStart:

setMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setMotechEvent(MotechEvent motechEvent)
   :outertype: RepeatingSchedulableJob

setRepeatCount
^^^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setRepeatCount(Integer repeatCount)
   :outertype: RepeatingSchedulableJob

setRepeatIntervalInMilliSeconds
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setRepeatIntervalInMilliSeconds(Long repeatIntervalInMilliSeconds)
   :outertype: RepeatingSchedulableJob

setStartTime
^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setStartTime(Date startTime)
   :outertype: RepeatingSchedulableJob

setUseOriginalFireTimeAfterMisfire
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public RepeatingSchedulableJob setUseOriginalFireTimeAfterMisfire(boolean useOriginalFireTimeAfterMisfire)
   :outertype: RepeatingSchedulableJob

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: RepeatingSchedulableJob

