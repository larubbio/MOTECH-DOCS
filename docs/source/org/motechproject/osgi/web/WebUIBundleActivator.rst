.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.osgi.web.exception HeaderFileMissingException

.. java:import:: org.motechproject.osgi.web.util WebBundleUtil

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.net URL

.. java:import:: java.util HashMap

.. java:import:: java.util Map

WebUIBundleActivator
====================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class WebUIBundleActivator extends org.motechproject.osgi.web.Activator

Methods
-------
moduleId
^^^^^^^^

.. java:method:: protected String moduleId()
   :outertype: WebUIBundleActivator

resourceFolder
^^^^^^^^^^^^^^

.. java:method:: protected String resourceFolder()
   :outertype: WebUIBundleActivator

resourceMappings
^^^^^^^^^^^^^^^^

.. java:method:: @Override protected Map<String, String> resourceMappings()
   :outertype: WebUIBundleActivator

start
^^^^^

.. java:method:: @Override public void start(BundleContext context)
   :outertype: WebUIBundleActivator

stop
^^^^

.. java:method:: public void stop(BundleContext context)
   :outertype: WebUIBundleActivator

