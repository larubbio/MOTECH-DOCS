JobBasicInfo
============

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public class JobBasicInfo

   JobBasicInfo is the class which contains information about scheduled job and its current state.

Fields
------
ACTIVITY_ACTIVE
^^^^^^^^^^^^^^^

.. java:field:: public static final String ACTIVITY_ACTIVE
   :outertype: JobBasicInfo

ACTIVITY_FINISHED
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String ACTIVITY_FINISHED
   :outertype: JobBasicInfo

ACTIVITY_NOTSTARTED
^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String ACTIVITY_NOTSTARTED
   :outertype: JobBasicInfo

JOBTYPE_CRON
^^^^^^^^^^^^

.. java:field:: public static final String JOBTYPE_CRON
   :outertype: JobBasicInfo

JOBTYPE_REPEATING
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String JOBTYPE_REPEATING
   :outertype: JobBasicInfo

JOBTYPE_RUNONCE
^^^^^^^^^^^^^^^

.. java:field:: public static final String JOBTYPE_RUNONCE
   :outertype: JobBasicInfo

STATUS_BLOCKED
^^^^^^^^^^^^^^

.. java:field:: public static final String STATUS_BLOCKED
   :outertype: JobBasicInfo

STATUS_ERROR
^^^^^^^^^^^^

.. java:field:: public static final String STATUS_ERROR
   :outertype: JobBasicInfo

STATUS_OK
^^^^^^^^^

.. java:field:: public static final String STATUS_OK
   :outertype: JobBasicInfo

STATUS_PAUSED
^^^^^^^^^^^^^

.. java:field:: public static final String STATUS_PAUSED
   :outertype: JobBasicInfo

Constructors
------------
JobBasicInfo
^^^^^^^^^^^^

.. java:constructor:: public JobBasicInfo()
   :outertype: JobBasicInfo

JobBasicInfo
^^^^^^^^^^^^

.. java:constructor:: public JobBasicInfo(String activity, String status, String name, String startDate, String nextFireDate, String endDate, String jobType, String info)
   :outertype: JobBasicInfo

Methods
-------
getActivity
^^^^^^^^^^^

.. java:method:: public String getActivity()
   :outertype: JobBasicInfo

getEndDate
^^^^^^^^^^

.. java:method:: public String getEndDate()
   :outertype: JobBasicInfo

getInfo
^^^^^^^

.. java:method:: public String getInfo()
   :outertype: JobBasicInfo

getJobType
^^^^^^^^^^

.. java:method:: public String getJobType()
   :outertype: JobBasicInfo

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: JobBasicInfo

getNextFireDate
^^^^^^^^^^^^^^^

.. java:method:: public String getNextFireDate()
   :outertype: JobBasicInfo

getStartDate
^^^^^^^^^^^^

.. java:method:: public String getStartDate()
   :outertype: JobBasicInfo

getStatus
^^^^^^^^^

.. java:method:: public String getStatus()
   :outertype: JobBasicInfo

setActivity
^^^^^^^^^^^

.. java:method:: public void setActivity(String activity)
   :outertype: JobBasicInfo

setEndDate
^^^^^^^^^^

.. java:method:: public void setEndDate(String endDate)
   :outertype: JobBasicInfo

setInfo
^^^^^^^

.. java:method:: public void setInfo(String info)
   :outertype: JobBasicInfo

setJobType
^^^^^^^^^^

.. java:method:: public void setJobType(String jobType)
   :outertype: JobBasicInfo

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: JobBasicInfo

setNextFireDate
^^^^^^^^^^^^^^^

.. java:method:: public void setNextFireDate(String nextFireDate)
   :outertype: JobBasicInfo

setStartDate
^^^^^^^^^^^^

.. java:method:: public void setStartDate(String startDate)
   :outertype: JobBasicInfo

setStatus
^^^^^^^^^

.. java:method:: public void setStatus(String status)
   :outertype: JobBasicInfo

