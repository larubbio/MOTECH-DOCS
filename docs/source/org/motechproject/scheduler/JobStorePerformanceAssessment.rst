.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.api NanoStopWatch

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.quartz CouchDbJobStoreException

.. java:import:: org.motechproject.quartz CouchDbStore

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.scheduler.factory MotechSchedulerFactoryBean

.. java:import:: org.motechproject.scheduler.impl MotechSchedulerServiceImpl

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.quartz Scheduler

.. java:import:: org.quartz SchedulerException

.. java:import:: org.quartz.impl.matchers GroupMatcher

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.io IOException

.. java:import:: java.util Date

.. java:import:: java.util HashMap

.. java:import:: java.util Map

JobStorePerformanceAssessment
=============================

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class JobStorePerformanceAssessment

Fields
------
applicationContext
^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  ApplicationContext applicationContext
   :outertype: JobStorePerformanceAssessment

couchSchedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  MotechSchedulerFactoryBean couchSchedulerFactoryBean
   :outertype: JobStorePerformanceAssessment

couchdbSettingsFacade
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired @Qualifier  SettingsFacade couchdbSettingsFacade
   :outertype: JobStorePerformanceAssessment

couchdbStore
^^^^^^^^^^^^

.. java:field::  CouchDbStore couchdbStore
   :outertype: JobStorePerformanceAssessment

eventListenerRegistryService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  EventListenerRegistryService eventListenerRegistryService
   :outertype: JobStorePerformanceAssessment

jdbcSchedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  MotechSchedulerFactoryBean jdbcSchedulerFactoryBean
   :outertype: JobStorePerformanceAssessment

jdbcSettingsFacade
^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired @Qualifier  SettingsFacade jdbcSettingsFacade
   :outertype: JobStorePerformanceAssessment

Methods
-------
schedulingJobsInCouchStore
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void schedulingJobsInCouchStore() throws Exception
   :outertype: JobStorePerformanceAssessment

schedulingJobsInJdbcStore
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void schedulingJobsInJdbcStore() throws Exception
   :outertype: JobStorePerformanceAssessment

setup
^^^^^

.. java:method:: @Before public void setup() throws IOException, CouchDbJobStoreException
   :outertype: JobStorePerformanceAssessment

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown() throws SchedulerException
   :outertype: JobStorePerformanceAssessment

