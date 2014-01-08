.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Test

.. java:import:: org.motechproject.config.core.filters ConfigFileFilter

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.util List

ConfigFileFilterIT
==================

.. java:package:: org.motechproject.config.core.filestore
   :noindex:

.. java:type:: public class ConfigFileFilterIT

Methods
-------
shouldAcceptPlatformCorePropertiesFileAtRootConfigDir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAcceptPlatformCorePropertiesFileAtRootConfigDir()
   :outertype: ConfigFileFilterIT

shouldAcceptPropertiesFileAtCorrectParentDir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAcceptPropertiesFileAtCorrectParentDir()
   :outertype: ConfigFileFilterIT

shouldRejectBootstrapPropertiesAtRootConfigDir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectBootstrapPropertiesAtRootConfigDir()
   :outertype: ConfigFileFilterIT

shouldRejectNonPropertiesFilesAtCorrectParentDir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectNonPropertiesFilesAtCorrectParentDir()
   :outertype: ConfigFileFilterIT

shouldRejectPropertiesFileAtRootConfigDir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectPropertiesFileAtRootConfigDir()
   :outertype: ConfigFileFilterIT

shouldRetainOnlyPlatformConfigFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRetainOnlyPlatformConfigFile() throws IOException
   :outertype: ConfigFileFilterIT

