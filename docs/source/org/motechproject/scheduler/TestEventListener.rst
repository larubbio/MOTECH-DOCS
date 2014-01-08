.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeConstants

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.scheduler.domain DayOfWeekSchedulableJob

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

.. java:import:: org.motechproject.scheduler.domain JobDetailedInfo

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.motechproject.scheduler.exception MotechSchedulerException

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.quartz JobKey

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz Trigger

.. java:import:: org.quartz.impl.matchers GroupMatcher

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

TestEventListener
=================

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type::  class TestEventListener implements EventListener

Methods
-------
getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: TestEventListener

getReceivedEvents
^^^^^^^^^^^^^^^^^

.. java:method:: public List<MotechEvent> getReceivedEvents()
   :outertype: TestEventListener

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: TestEventListener

