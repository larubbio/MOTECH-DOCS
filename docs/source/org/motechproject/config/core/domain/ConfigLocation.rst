.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io.filefilter TrueFileFilter

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.filters ConfigFileFilter

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.core.io UrlResource

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.net MalformedURLException

.. java:import:: java.util Collection

.. java:import:: java.util List

ConfigLocation
==============

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public class ConfigLocation

   Defines a MOTECH configuration location. If the given location starts with a leading file separator character, the location is treated as a file system directory. Otherwise, it is treated as a classpath location.

Constructors
------------
ConfigLocation
^^^^^^^^^^^^^^

.. java:constructor:: public ConfigLocation(String configLocation)
   :outertype: ConfigLocation

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: ConfigLocation

getExistingConfigFiles
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<File> getExistingConfigFiles()
   :outertype: ConfigLocation

getFile
^^^^^^^

.. java:method:: public File getFile(String fileName, FileAccessType accessType)
   :outertype: ConfigLocation

   This method Returns the \ :java:ref:`java.io.File`\  object for the given file name relative to the config location. It also checks for the requested file accessibility. If the requested access type check is \ :java:ref:`ConfigLocation.FileAccessType.READABLE`\ , the file's existence and readability will be checked. Similarly, if the requested access type check is \ :java:ref:`ConfigLocation.FileAccessType.WRITABLE`\ , then the write accessibility to the file will be checked. If the file does not exists, write accessibility of its ancestors will be checked.

   :param fileName: Name of the file to be added to the config location.
   :param accessType: One of \ :java:ref:`ConfigLocation.FileAccessType.READABLE`\  or \ :java:ref:`ConfigLocation.FileAccessType.WRITABLE`\ .
   :return: File relative to the config location.

getLocation
^^^^^^^^^^^

.. java:method:: public String getLocation()
   :outertype: ConfigLocation

getUrlResource
^^^^^^^^^^^^^^

.. java:method::  UrlResource getUrlResource() throws MalformedURLException
   :outertype: ConfigLocation

hasPlatformConfigurationFile
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean hasPlatformConfigurationFile()
   :outertype: ConfigLocation

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ConfigLocation

toResource
^^^^^^^^^^

.. java:method:: public Resource toResource()
   :outertype: ConfigLocation

   Resource corresponding to the config location.

   :return: resource

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ConfigLocation

