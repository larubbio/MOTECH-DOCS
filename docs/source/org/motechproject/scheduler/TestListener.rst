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

TestListener
============

.. java:package:: org.motechproject.scheduler
   :noindex:

.. java:type::  class TestListener implements EventListener

Fields
------
count
^^^^^

.. java:field:: volatile int count
   :outertype: TestListener

identifier
^^^^^^^^^^

.. java:field::  String identifier
   :outertype: TestListener

maxJobs
^^^^^^^

.. java:field:: final int maxJobs
   :outertype: TestListener

repeat
^^^^^^

.. java:field:: final int repeat
   :outertype: TestListener

report
^^^^^^

.. java:field::  String report
   :outertype: TestListener

timer
^^^^^

.. java:field::  NanoStopWatch timer
   :outertype: TestListener

Constructors
------------
TestListener
^^^^^^^^^^^^

.. java:constructor::  TestListener(String identifier, int maxJobs, int repeat)
   :outertype: TestListener

Methods
-------
getCount
^^^^^^^^

.. java:method:: public int getCount()
   :outertype: TestListener

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: TestListener

getReport
^^^^^^^^^

.. java:method:: public String getReport()
   :outertype: TestListener

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: TestListener

