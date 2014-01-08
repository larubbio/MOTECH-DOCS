.. java:import:: org.junit Before

.. java:import:: org.junit Rule

.. java:import:: org.junit Test

.. java:import:: org.junit.rules ExpectedException

.. java:import:: org.mockito InOrder

.. java:import:: org.mockito Matchers

.. java:import:: org.mockito Mock

.. java:import:: org.mockito Mockito

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.bootstrap Environment

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.core.filestore ConfigFileReader

.. java:import:: org.motechproject.config.core.filestore ConfigLocationFileStore

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.nio.file FileSystemException

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Properties

CoreConfigurationServiceImplTest
================================

.. java:package:: org.motechproject.config.core.service.impl
   :noindex:

.. java:type:: public class CoreConfigurationServiceImplTest

Fields
------
expectedException
^^^^^^^^^^^^^^^^^

.. java:field:: @Rule public ExpectedException expectedException
   :outertype: CoreConfigurationServiceImplTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: CoreConfigurationServiceImplTest

shouldAddConfigLocation
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddConfigLocation() throws FileSystemException
   :outertype: CoreConfigurationServiceImplTest

shouldGetConfigLocation
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetConfigLocation()
   :outertype: CoreConfigurationServiceImplTest

shouldLoadPropertiesInTheCorrectOrder
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldLoadPropertiesInTheCorrectOrder() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldReturnBootStrapConfigFromFileAtDefaultLocation_If_NoEnvironmentVariablesAreSpecified
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnBootStrapConfigFromFileAtDefaultLocation_If_NoEnvironmentVariablesAreSpecified() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldReturnBootStrapConfigValuesFromEnvironmentVariableWhenMotechConfigDirIsNotSpecified
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnBootStrapConfigValuesFromEnvironmentVariableWhenMotechConfigDirIsNotSpecified() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldReturnBootstrapConfigFromFileSpecifiedInTheEnvironmentVariable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnBootstrapConfigFromFileSpecifiedInTheEnvironmentVariable() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldReturnDefaultValueIfConfigSourceIsNotSpecified
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnDefaultValueIfConfigSourceIsNotSpecified()
   :outertype: CoreConfigurationServiceImplTest

shouldReturnDefaultValueIfTenantIdIsNotSpecified
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnDefaultValueIfTenantIdIsNotSpecified()
   :outertype: CoreConfigurationServiceImplTest

shouldReturnNullIfNoneOfTheFilesInTheDefaultLocationIsReadable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnNullIfNoneOfTheFilesInTheDefaultLocationIsReadable() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldSaveBootstrapConfigToPropertiesFileInDefaultLocation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveBootstrapConfigToPropertiesFileInDefaultLocation() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldThrowExceptionIfConfigFileReaderCanNotReadFileSpecifiedInEnvironmentVariable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfConfigFileReaderCanNotReadFileSpecifiedInEnvironmentVariable() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldThrowExceptionIfNoneOfTheConfigLocationsAreReadable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfNoneOfTheConfigLocationsAreReadable()
   :outertype: CoreConfigurationServiceImplTest

shouldThrowExceptionIfReadingTheBootstrapFileFails
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfReadingTheBootstrapFileFails() throws IOException
   :outertype: CoreConfigurationServiceImplTest

shouldThrowMotechConfigurationExceptionIfSavingBootstrapPropertiesFailed
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowMotechConfigurationExceptionIfSavingBootstrapPropertiesFailed() throws IOException
   :outertype: CoreConfigurationServiceImplTest

