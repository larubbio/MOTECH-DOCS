.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InOrder

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.domain AdminSettings

.. java:import:: org.motechproject.admin.service.impl SettingsServiceImpl

.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: org.motechproject.admin.settings SettingsOption

.. java:import:: org.motechproject.config.monitor ConfigFileMonitor

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.security.web.savedrequest Enumerator

.. java:import:: java.io IOException

.. java:import:: java.net URL

.. java:import:: java.util AbstractMap

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

SettingsServiceTest
===================

.. java:package:: org.motechproject.admin.service
   :noindex:

.. java:type:: public class SettingsServiceTest

Fields
------
bundle
^^^^^^

.. java:field:: @Mock  Bundle bundle
   :outertype: SettingsServiceTest

bundleContext
^^^^^^^^^^^^^

.. java:field:: @Mock  BundleContext bundleContext
   :outertype: SettingsServiceTest

bundleProperty
^^^^^^^^^^^^^^

.. java:field::  Properties bundleProperty
   :outertype: SettingsServiceTest

configurationService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ConfigurationService configurationService
   :outertype: SettingsServiceTest

motechSettings
^^^^^^^^^^^^^^

.. java:field:: @Mock  MotechSettings motechSettings
   :outertype: SettingsServiceTest

settingsService
^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  SettingsService settingsService
   :outertype: SettingsServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: SettingsServiceTest

shouldAddSettingsPath
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddSettingsPath() throws IOException
   :outertype: SettingsServiceTest

testGetBundleSettings
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleSettings() throws IOException
   :outertype: SettingsServiceTest

testGetSettings
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetSettings()
   :outertype: SettingsServiceTest

testSaveBundleSettings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSaveBundleSettings() throws IOException
   :outertype: SettingsServiceTest

