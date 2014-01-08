.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.server.api BundleLoader

.. java:import:: org.motechproject.server.api BundleLoadingException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.web.context ServletContextAware

.. java:import:: javax.servlet ServletContext

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io FileOutputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io InputStreamReader

.. java:import:: java.lang.reflect Field

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.lang.reflect Method

.. java:import:: java.net URL

.. java:import:: java.util Arrays

.. java:import:: java.util Enumeration

.. java:import:: java.util Properties

.. java:import:: java.util ResourceBundle

.. java:import:: java.util.jar JarEntry

.. java:import:: java.util.jar JarFile

JspBundleLoader
===============

.. java:package:: org.motechproject.server.impl
   :noindex:

.. java:type:: public class JspBundleLoader implements BundleLoader, ServletContextAware

Methods
-------
loadBundle
^^^^^^^^^^

.. java:method:: @SuppressWarnings @Override public void loadBundle(Bundle bundle) throws BundleLoadingException
   :outertype: JspBundleLoader

reloadBundles
^^^^^^^^^^^^^

.. java:method:: public static void reloadBundles()
   :outertype: JspBundleLoader

setServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setServletContext(ServletContext servletContext)
   :outertype: JspBundleLoader

