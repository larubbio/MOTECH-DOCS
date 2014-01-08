.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Captor

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.domain ModulePropertiesRecord

.. java:import:: org.motechproject.config.repository AllModuleProperties

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.config.repository AllSettings

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.springframework.core.io ResourceLoader

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Properties

ConfigurationServiceTest
========================

.. java:package:: org.motechproject.config.service.impl
   :noindex:

.. java:type:: public class ConfigurationServiceTest

Fields
------
propertiesCaptor
^^^^^^^^^^^^^^^^

.. java:field:: @Captor  ArgumentCaptor<List<ModulePropertiesRecord>> propertiesCaptor
   :outertype: ConfigurationServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: ConfigurationServiceTest

shouldBulkAddOrUpdateConfigsWhileProcessingExistingConfigs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBulkAddOrUpdateConfigsWhileProcessingExistingConfigs()
   :outertype: ConfigurationServiceTest

shouldBulkDeleteProperties
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBulkDeleteProperties()
   :outertype: ConfigurationServiceTest

shouldDeleteModulePropertiesRecordCorrespondingToAFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteModulePropertiesRecordCorrespondingToAFile()
   :outertype: ConfigurationServiceTest

shouldGetEmptyPropertiesWhenNoPropertiesAreFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetEmptyPropertiesWhenNoPropertiesAreFound() throws java.io.IOException
   :outertype: ConfigurationServiceTest

shouldGetModuleProperties
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetModuleProperties() throws java.io.IOException
   :outertype: ConfigurationServiceTest

shouldIndicateThatConfigFilesAreNotRequiredWhenConfigSourceIsUI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldIndicateThatConfigFilesAreNotRequiredWhenConfigSourceIsUI() throws IOException
   :outertype: ConfigurationServiceTest

shouldIndicateThatConfigFilesAreNotRequiredWhenPlatformConfigurationFileIsPresent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldIndicateThatConfigFilesAreNotRequiredWhenPlatformConfigurationFileIsPresent() throws IOException
   :outertype: ConfigurationServiceTest

shouldIndicateThatConfigFilesAreRequiredWhenPlatformConfigurationFileIsMissing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldIndicateThatConfigFilesAreRequiredWhenPlatformConfigurationFileIsMissing() throws IOException
   :outertype: ConfigurationServiceTest

shouldLoadBootstrapDBConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldLoadBootstrapDBConfiguration()
   :outertype: ConfigurationServiceTest

shouldSaveBootstrapConfig
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveBootstrapConfig() throws IOException
   :outertype: ConfigurationServiceTest

shouldUpdateModuleProperties
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdateModuleProperties()
   :outertype: ConfigurationServiceTest

shouldUpdateMotechSettings
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdateMotechSettings()
   :outertype: ConfigurationServiceTest

shouldUpdatePlatformCoreConfigWhileProcessingExistingConfigs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdatePlatformCoreConfigWhileProcessingExistingConfigs()
   :outertype: ConfigurationServiceTest

