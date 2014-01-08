.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.osgi.service.http HttpContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io BufferedReader

.. java:import:: java.io File

.. java:import:: java.io FileReader

.. java:import:: java.io IOException

.. java:import:: java.net URL

FileSystemAwareUIHttpContext
============================

.. java:package:: org.motechproject.osgi.web.ext
   :noindex:

.. java:type:: public class FileSystemAwareUIHttpContext extends UiHttpContext

Constructors
------------
FileSystemAwareUIHttpContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public FileSystemAwareUIHttpContext(HttpContext context, String resourceRootDirectoryPath)
   :outertype: FileSystemAwareUIHttpContext

Methods
-------
getResource
^^^^^^^^^^^

.. java:method:: @Override public URL getResource(String name)
   :outertype: FileSystemAwareUIHttpContext

getResourceRootDirectoryPath
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getResourceRootDirectoryPath()
   :outertype: FileSystemAwareUIHttpContext

