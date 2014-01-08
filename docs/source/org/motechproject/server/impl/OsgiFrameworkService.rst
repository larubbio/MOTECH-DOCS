.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io.filefilter SuffixFileFilter

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.eclipse.gemini.blueprint OsgiException

.. java:import:: org.motechproject.server.api BundleLoader

.. java:import:: org.motechproject.server.api BundleLoadingException

.. java:import:: org.motechproject.server.api JarInformation

.. java:import:: org.motechproject.server.ex CriticalBundleException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework BundleEvent

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework Constants

.. java:import:: org.osgi.framework InvalidSyntaxException

.. java:import:: org.osgi.framework ServiceEvent

.. java:import:: org.osgi.framework ServiceListener

.. java:import:: org.osgi.framework.launch Framework

.. java:import:: org.osgi.service.event EventConstants

.. java:import:: org.osgi.service.event EventHandler

.. java:import:: org.osgi.service.http HttpService

.. java:import:: org.osgi.util.tracker BundleTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.context ApplicationContextAware

.. java:import:: org.springframework.web.context WebApplicationContext

.. java:import:: javax.servlet ServletContext

.. java:import:: java.io File

.. java:import:: java.io FileFilter

.. java:import:: java.io IOException

.. java:import:: java.lang.reflect Proxy

.. java:import:: java.net MalformedURLException

.. java:import:: java.net URL

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util Dictionary

.. java:import:: java.util HashMap

.. java:import:: java.util Hashtable

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

.. java:import:: java.util.concurrent ExecutorService

.. java:import:: java.util.concurrent Executors

.. java:import:: java.util.jar JarInputStream

.. java:import:: java.util.jar Manifest

OsgiFrameworkService
====================

.. java:package:: org.motechproject.server.impl
   :noindex:

.. java:type:: public class OsgiFrameworkService implements ApplicationContextAware

   Class for initializing and starting the OSGi framework. Also registers a startup listener and HttpService listener and store bundle classloaders.

Methods
-------
allowStartup
^^^^^^^^^^^^

.. java:method:: public void allowStartup()
   :outertype: OsgiFrameworkService

getBundleClassLoaderLookup
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Map<String, ClassLoader> getBundleClassLoaderLookup()
   :outertype: OsgiFrameworkService

getBundleLocationByBundleId
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getBundleLocationByBundleId(String bundleId)
   :outertype: OsgiFrameworkService

getClassLoaderBySymbolicName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public ClassLoader getClassLoaderBySymbolicName(String bundleSymbolicName)
   :outertype: OsgiFrameworkService

   The current OSGi (4.2) doesn't provide a standard way to retrieve the bundle ClassLoader. So we have to use this as a workaround.

   :param bundleSymbolicName:
   :return: The ClassLoader of the bundle

getExternalBundleFolder
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getExternalBundleFolder()
   :outertype: OsgiFrameworkService

getFragmentSubFolder
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getFragmentSubFolder()
   :outertype: OsgiFrameworkService

getInternalBundleFolder
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getInternalBundleFolder()
   :outertype: OsgiFrameworkService

httpServiceRegistered
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void httpServiceRegistered()
   :outertype: OsgiFrameworkService

setApplicationContext
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setApplicationContext(ApplicationContext ctx)
   :outertype: OsgiFrameworkService

setBundleLoaders
^^^^^^^^^^^^^^^^

.. java:method:: public void setBundleLoaders(List<BundleLoader> bundleLoaders)
   :outertype: OsgiFrameworkService

setExternalBundleFolder
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setExternalBundleFolder(String externalBundleFolder)
   :outertype: OsgiFrameworkService

setFragmentSubFolder
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setFragmentSubFolder(String fragmentSubFolder)
   :outertype: OsgiFrameworkService

setInternalBundleFolder
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setInternalBundleFolder(String bundleFolder)
   :outertype: OsgiFrameworkService

setOsgiFramework
^^^^^^^^^^^^^^^^

.. java:method:: public void setOsgiFramework(Framework osgiFramework)
   :outertype: OsgiFrameworkService

start
^^^^^

.. java:method:: public void start()
   :outertype: OsgiFrameworkService

   Initialize, install and start bundles and the OSGi framework

stop
^^^^

.. java:method:: public void stop()
   :outertype: OsgiFrameworkService

   Stop the OSGi framework.

