.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.quartz JobDetail

.. java:import:: org.quartz JobKey

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz.impl.triggers SimpleTriggerImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util Date

.. java:import:: java.util List

CouchDbStoreSchedulerIT
=======================

.. java:package:: org.motechproject.scheduler.quartz
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class CouchDbStoreSchedulerIT

Fields
------
eventListenerRegistry
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  EventListenerRegistryService eventListenerRegistry
   :outertype: CouchDbStoreSchedulerIT

scheduler
^^^^^^^^^

.. java:field::  Scheduler scheduler
   :outertype: CouchDbStoreSchedulerIT

schedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  MotechSchedulerFactoryBean schedulerFactoryBean
   :outertype: CouchDbStoreSchedulerIT

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: CouchDbStoreSchedulerIT

shouldScheduleAndFireSimpleTrigger
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldScheduleAndFireSimpleTrigger() throws SchedulerException, InterruptedException
   :outertype: CouchDbStoreSchedulerIT

