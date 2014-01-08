.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.util Properties

ConfigFileReader
================

.. java:package:: org.motechproject.config.core.filestore
   :noindex:

.. java:type:: public interface ConfigFileReader

   The \ ``ConfigFileReader``\  class is used to load \ ``Properties``\  from a file. *

Methods
-------
getProperties
^^^^^^^^^^^^^

.. java:method::  Properties getProperties(File file) throws IOException
   :outertype: ConfigFileReader

   Reads a properties file and returns \ ``Properties``\  object.

   :param file: - file containing properties to be read *

