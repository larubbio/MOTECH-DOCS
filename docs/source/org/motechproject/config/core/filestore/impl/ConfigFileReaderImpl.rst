.. java:import:: org.motechproject.config.core.filestore ConfigFileReader

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.util Properties

ConfigFileReaderImpl
====================

.. java:package:: org.motechproject.config.core.filestore.impl
   :noindex:

.. java:type:: @Component public class ConfigFileReaderImpl implements ConfigFileReader

Methods
-------
getProperties
^^^^^^^^^^^^^

.. java:method:: @Override public Properties getProperties(File file) throws IOException
   :outertype: ConfigFileReaderImpl

