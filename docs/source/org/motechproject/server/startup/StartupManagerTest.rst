.. java:import:: org.junit Assert

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.osgi.service.event Event

.. java:import:: org.osgi.service.event EventAdmin

StartupManagerTest
==================

.. java:package:: org.motechproject.server.startup
   :noindex:

.. java:type:: public class StartupManagerTest

Fields
------
configLoader
^^^^^^^^^^^^

.. java:field:: @Mock  ConfigLoader configLoader
   :outertype: StartupManagerTest

configurationService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ConfigurationService configurationService
   :outertype: StartupManagerTest

settingsRecord
^^^^^^^^^^^^^^

.. java:field:: @Mock  SettingsRecord settingsRecord
   :outertype: StartupManagerTest

startupManager
^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  StartupManager startupManager
   :outertype: StartupManagerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: StartupManagerTest

shouldNotTryToLoadDbSettingsIfConfigurationFilesAreStillRequired
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotTryToLoadDbSettingsIfConfigurationFilesAreStillRequired()
   :outertype: StartupManagerTest

shouldSetPlatformStateToNeedBootstrapIfNoBootstrapConfigFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSetPlatformStateToNeedBootstrapIfNoBootstrapConfigFound()
   :outertype: StartupManagerTest

testNoSettings
^^^^^^^^^^^^^^

.. java:method:: @Test public void testNoSettings()
   :outertype: StartupManagerTest

