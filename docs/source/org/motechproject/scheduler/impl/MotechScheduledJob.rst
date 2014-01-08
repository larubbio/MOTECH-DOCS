.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.quartz Job

.. java:import:: org.quartz JobDataMap

.. java:import:: org.quartz JobDetail

.. java:import:: org.quartz JobExecutionContext

.. java:import:: org.quartz JobExecutionException

.. java:import:: org.quartz SchedulerContext

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz Trigger

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: java.util Map

MotechScheduledJob
==================

.. java:package:: org.motechproject.scheduler.impl
   :noindex:

.. java:type:: public class MotechScheduledJob implements Job

Methods
-------
execute
^^^^^^^

.. java:method:: @Override @SuppressWarnings public void execute(JobExecutionContext jobExecutionContext) throws JobExecutionException
   :outertype: MotechScheduledJob

