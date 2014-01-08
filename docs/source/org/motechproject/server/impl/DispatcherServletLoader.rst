.. java:import:: org.motechproject.server.api BundleLoader

.. java:import:: org.motechproject.server.api BundleLoadingException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.springframework.context ApplicationContext

DispatcherServletLoader
=======================

.. java:package:: org.motechproject.server.impl
   :noindex:

.. java:type:: public class DispatcherServletLoader implements BundleLoader

Methods
-------
loadBundle
^^^^^^^^^^

.. java:method:: @Override public void loadBundle(Bundle bundle) throws BundleLoadingException
   :outertype: DispatcherServletLoader

