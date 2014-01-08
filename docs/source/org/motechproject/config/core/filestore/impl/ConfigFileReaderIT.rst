.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Test

.. java:import:: org.motechproject.config.core.filestore ConfigFileReader

.. java:import:: org.motechproject.config.core.filestore.impl ConfigFileReaderImpl

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.net URL

.. java:import:: java.util Properties

ConfigFileReaderIT
==================

.. java:package:: org.motechproject.config.core.filestore.impl
   :noindex:

.. java:type:: public class ConfigFileReaderIT

Methods
-------
shouldReturnProperties
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnProperties() throws Exception
   :outertype: ConfigFileReaderIT

shouldThrowExceptionIfUnableToLoadTheFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfUnableToLoadTheFile() throws IOException
   :outertype: ConfigFileReaderIT

