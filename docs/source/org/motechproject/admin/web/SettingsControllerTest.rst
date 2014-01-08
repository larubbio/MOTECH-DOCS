.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.domain AdminSettings

.. java:import:: org.motechproject.admin.service SettingsService

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: org.motechproject.admin.settings SettingsOption

.. java:import:: org.motechproject.admin.web.controller SettingsController

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.io IOException

.. java:import:: java.util AbstractMap

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Map

SettingsControllerTest
======================

.. java:package:: org.motechproject.admin.web
   :noindex:

.. java:type:: public class SettingsControllerTest

Fields
------
bundleSettings
^^^^^^^^^^^^^^

.. java:field:: @Mock  Settings bundleSettings
   :outertype: SettingsControllerTest

bundleSettingsList
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  List<Settings> bundleSettingsList
   :outertype: SettingsControllerTest

controller
^^^^^^^^^^

.. java:field:: @InjectMocks  SettingsController controller
   :outertype: SettingsControllerTest

httpServletRequest
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  HttpServletRequest httpServletRequest
   :outertype: SettingsControllerTest

paramMap
^^^^^^^^

.. java:field:: @Mock  Map<Object, Object> paramMap
   :outertype: SettingsControllerTest

platformSettings
^^^^^^^^^^^^^^^^

.. java:field:: @Mock  Settings platformSettings
   :outertype: SettingsControllerTest

settingsService
^^^^^^^^^^^^^^^

.. java:field:: @Mock  SettingsService settingsService
   :outertype: SettingsControllerTest

statusMessageService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  StatusMessageService statusMessageService
   :outertype: SettingsControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: SettingsControllerTest

testGetBundleSettings
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleSettings() throws IOException
   :outertype: SettingsControllerTest

testGetPlatformSettings
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetPlatformSettings()
   :outertype: SettingsControllerTest

testSaveBundleSettings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSaveBundleSettings() throws IOException
   :outertype: SettingsControllerTest

testSavePlatformSettings
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSavePlatformSettings() throws IOException
   :outertype: SettingsControllerTest

