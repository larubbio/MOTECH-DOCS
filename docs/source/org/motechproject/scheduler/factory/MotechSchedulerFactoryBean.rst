.. java:import:: org.motechproject.scheduler.exception SchedulerInstantiationException

.. java:import:: org.motechproject.scheduler.exception SchedulerShutdownException

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.quartz Scheduler

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.scheduling.quartz SchedulerFactoryBean

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.annotation PostConstruct

.. java:import:: javax.annotation PreDestroy

.. java:import:: java.util Properties

MotechSchedulerFactoryBean
==========================

.. java:package:: org.motechproject.scheduler.factory
   :noindex:

.. java:type:: @Component public class MotechSchedulerFactoryBean

   The \ ``MotechSchedulerFactoryBean``\  is used to created scheduler and start it.

Constructors
------------
MotechSchedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechSchedulerFactoryBean(ApplicationContext applicationContext, SettingsFacade schedulerSettings)
   :outertype: MotechSchedulerFactoryBean

Methods
-------
getQuartzScheduler
^^^^^^^^^^^^^^^^^^

.. java:method:: public Scheduler getQuartzScheduler()
   :outertype: MotechSchedulerFactoryBean

getQuartzSchedulerFactoryBean
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public SchedulerFactoryBean getQuartzSchedulerFactoryBean()
   :outertype: MotechSchedulerFactoryBean

init
^^^^

.. java:method:: @PostConstruct public void init()
   :outertype: MotechSchedulerFactoryBean

shutdown
^^^^^^^^

.. java:method:: @PreDestroy public void shutdown()
   :outertype: MotechSchedulerFactoryBean

