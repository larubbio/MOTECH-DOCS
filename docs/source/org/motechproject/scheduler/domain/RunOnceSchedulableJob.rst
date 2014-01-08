.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.io Serializable

.. java:import:: java.util Date

RunOnceSchedulableJob
=====================

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public final class RunOnceSchedulableJob implements Serializable

   Run Once Schedulable Job - a data carrier class for a job scheduled in the future that can be fired only once

   This class is immutable

   User: Igor (iopushnyev@2paths.com) Date: 16/02/11 Time: 1:43 PM

Constructors
------------
RunOnceSchedulableJob
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public RunOnceSchedulableJob(MotechEvent motechEvent, Date startDate)
   :outertype: RunOnceSchedulableJob

   Constructor

   :param motechEvent: - event data message that will be send by Motech Scheduler when this job is fired
   :param startDate: - date and time when the job fill be fired

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: RunOnceSchedulableJob

getMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public MotechEvent getMotechEvent()
   :outertype: RunOnceSchedulableJob

getStartDate
^^^^^^^^^^^^

.. java:method:: public Date getStartDate()
   :outertype: RunOnceSchedulableJob

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: RunOnceSchedulableJob

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: RunOnceSchedulableJob

