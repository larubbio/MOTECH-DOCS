.. java:import:: org.quartz Job

.. java:import:: org.quartz JobExecutionContext

.. java:import:: org.quartz JobExecutionException

TestJobHandler
==============

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: public class TestJobHandler implements Job

Fields
------
invoked
^^^^^^^

.. java:field:: static boolean invoked
   :outertype: TestJobHandler

Methods
-------
execute
^^^^^^^

.. java:method:: @Override public void execute(JobExecutionContext context) throws JobExecutionException
   :outertype: TestJobHandler

isInvoked
^^^^^^^^^

.. java:method:: public static boolean isInvoked()
   :outertype: TestJobHandler

