.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.osgi.framework BundleActivator

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

Activator
=========

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class Activator implements BundleActivator

Methods
-------
start
^^^^^

.. java:method:: @Override public void start(BundleContext bundleContext)
   :outertype: Activator

stop
^^^^

.. java:method:: @Override public void stop(BundleContext context)
   :outertype: Activator

