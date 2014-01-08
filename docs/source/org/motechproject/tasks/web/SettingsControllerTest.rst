.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.tasks.domain SettingsDto

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

SettingsControllerTest
======================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @RunWith public class SettingsControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: SettingsControllerTest

testGetSettings
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetSettings()
   :outertype: SettingsControllerTest

testSaveSettings
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSaveSettings() throws BundleException
   :outertype: SettingsControllerTest

testSaveSettingsEmptyProperty
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSaveSettingsEmptyProperty() throws BundleException
   :outertype: SettingsControllerTest

