.. java:import:: org.motechproject.server.impl OsgiFrameworkService

.. java:import:: org.motechproject.server.impl OsgiListener

.. java:import:: java.io IOException

.. java:import:: java.net URL

FileLocator
===========

.. java:package:: org.eclipse.core.runtime
   :noindex:

.. java:type:: public final class FileLocator

   This class allows to load urls starting with bundle://. The openmrs-api module requires this hack for loading its xml classpath contexts in OSGi.

Methods
-------
resolve
^^^^^^^

.. java:method:: public static URL resolve(URL url) throws IOException
   :outertype: FileLocator

