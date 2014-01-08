.. java:import:: org.apache.commons.vfs FileChangeEvent

.. java:import:: org.apache.commons.vfs FileObject

.. java:import:: org.apache.commons.vfs FileSystemException

.. java:import:: org.apache.commons.vfs VFS

.. java:import:: org.apache.commons.vfs.impl DefaultFileMonitor

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito InOrder

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito.runners MockitoJUnitRunner

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.nio.file Files

.. java:import:: java.nio.file Path

.. java:import:: java.util List

ConfigFileMonitorTest
=====================

.. java:package:: org.motechproject.config.monitor
   :noindex:

.. java:type:: @RunWith public class ConfigFileMonitorTest

Fields
------
configLoader
^^^^^^^^^^^^

.. java:field:: @Mock  ConfigLoader configLoader
   :outertype: ConfigFileMonitorTest

coreConfigurationService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  CoreConfigurationService coreConfigurationService
   :outertype: ConfigFileMonitorTest

Methods
-------
shouldDeleteConfigWhenFileIsDeleted
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteConfigWhenFileIsDeleted() throws FileSystemException
   :outertype: ConfigFileMonitorTest

shouldNotSaveConfigWhenNewFileCreatedIsNotSupported
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveConfigWhenNewFileCreatedIsNotSupported() throws IOException
   :outertype: ConfigFileMonitorTest

shouldNotStartFileMonitorIfConfigLoaderThrowsException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotStartFileMonitorIfConfigLoaderThrowsException() throws IOException
   :outertype: ConfigFileMonitorTest

shouldProcessExistingFilesAndStartFileMonitorWhileInitializing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldProcessExistingFilesAndStartFileMonitorWhileInitializing() throws IOException
   :outertype: ConfigFileMonitorTest

shouldSaveConfigWhenFileIsChanged
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveConfigWhenFileIsChanged() throws IOException
   :outertype: ConfigFileMonitorTest

shouldSaveConfigWhenNewFileCreated
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveConfigWhenNewFileCreated() throws IOException
   :outertype: ConfigFileMonitorTest

shouldUpdateFileMonitoringLocation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdateFileMonitoringLocation() throws FileSystemException
   :outertype: ConfigFileMonitorTest

