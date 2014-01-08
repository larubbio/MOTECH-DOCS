.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Captor

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.springframework.core.io DefaultResourceLoader

.. java:import:: org.springframework.core.io UrlResource

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.net MalformedURLException

.. java:import:: java.util Arrays

.. java:import:: java.util List

ConfigLoaderTest
================

.. java:package:: org.motechproject.server.config.service
   :noindex:

.. java:type:: public class ConfigLoaderTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: ConfigLoaderTest

shouldLoadDefaultActiveMq
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldLoadDefaultActiveMq()
   :outertype: ConfigLoaderTest

shouldLoadSupportedFilesFromGivenConfigLocation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldLoadSupportedFilesFromGivenConfigLocation() throws IOException
   :outertype: ConfigLoaderTest

shouldReturnFilesInConfigLocation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnFilesInConfigLocation() throws IOException
   :outertype: ConfigLoaderTest

shouldThrowExceptionIfErrorReadingSettingsFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfErrorReadingSettingsFile() throws MalformedURLException
   :outertype: ConfigLoaderTest

testActiveMqPropertiesLoading
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testActiveMqPropertiesLoading()
   :outertype: ConfigLoaderTest

testMotechSettingsLoading
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testMotechSettingsLoading()
   :outertype: ConfigLoaderTest

