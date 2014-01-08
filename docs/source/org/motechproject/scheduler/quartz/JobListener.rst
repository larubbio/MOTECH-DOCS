.. java:import:: org.quartz Job

.. java:import:: org.quartz JobExecutionContext

.. java:import:: org.quartz JobExecutionException

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util List

JobListener
===========

.. java:package:: org.motechproject.scheduler.quartz
   :noindex:

.. java:type:: public class JobListener implements Job

Constructors
------------
JobListener
^^^^^^^^^^^

.. java:constructor:: public JobListener()
   :outertype: JobListener

Methods
-------
execute
^^^^^^^

.. java:method:: @Override public void execute(JobExecutionContext context) throws JobExecutionException
   :outertype: JobListener

getFireTimes
^^^^^^^^^^^^

.. java:method:: public static List<Date> getFireTimes()
   :outertype: JobListener

