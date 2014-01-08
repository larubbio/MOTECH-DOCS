.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: java.io Serializable

JobId
=====

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public abstract class JobId implements Serializable

Constructors
------------
JobId
^^^^^

.. java:constructor:: public JobId(String subject, String id, String suffix)
   :outertype: JobId

JobId
^^^^^

.. java:constructor:: public JobId(MotechEvent motechEvent, String suffix)
   :outertype: JobId

Methods
-------
toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: JobId

value
^^^^^

.. java:method:: public String value()
   :outertype: JobId

