.. java:import:: org.apache.commons.vfs FileSystemException

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.monitor ConfigFileMonitor

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context.annotation Bean

.. java:import:: org.springframework.context.annotation Configuration

ConfigFileMonitorBeanFactory
============================

.. java:package:: org.motechproject.config.monitor.cnf
   :noindex:

.. java:type:: @Configuration public class ConfigFileMonitorBeanFactory

   Spring Config class to create ConfigFileMonitor bean.

Methods
-------
configFileMonitor
^^^^^^^^^^^^^^^^^

.. java:method:: @Bean @Autowired public ConfigFileMonitor configFileMonitor(ConfigLoader configLoader, ConfigurationService configurationService, CoreConfigurationService coreConfigurationService) throws FileSystemException
   :outertype: ConfigFileMonitorBeanFactory

