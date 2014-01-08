.. java:import:: org.apache.commons.vfs FileSystemException

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.monitor ConfigFileMonitor

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.service ConfigLoader

ConfigFileMonitorCnfTest
========================

.. java:package:: org.motechproject.config.monitor.cnf
   :noindex:

.. java:type:: public class ConfigFileMonitorCnfTest

Fields
------
configLoader
^^^^^^^^^^^^

.. java:field:: @Mock  ConfigLoader configLoader
   :outertype: ConfigFileMonitorCnfTest

configurationService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ConfigurationService configurationService
   :outertype: ConfigFileMonitorCnfTest

coreConfigurationService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  CoreConfigurationService coreConfigurationService
   :outertype: ConfigFileMonitorCnfTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: ConfigFileMonitorCnfTest

shouldCreateConfigFileMonitorBean_WhenConfigSourceIsFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateConfigFileMonitorBean_WhenConfigSourceIsFile() throws FileSystemException
   :outertype: ConfigFileMonitorCnfTest

shouldNotCreateConfigFileMonitorBean_WhenConfigSourceIsUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotCreateConfigFileMonitorBean_WhenConfigSourceIsUI() throws FileSystemException
   :outertype: ConfigFileMonitorCnfTest

