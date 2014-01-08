.. java:import:: org.osgi.framework BundleActivator

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.util Map

Activator
=========

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class Activator implements BundleActivator

Methods
-------
resourceMappings
^^^^^^^^^^^^^^^^

.. java:method:: protected Map<String, String> resourceMappings()
   :outertype: Activator

start
^^^^^

.. java:method:: @Override public void start(BundleContext context)
   :outertype: Activator

stop
^^^^

.. java:method:: public void stop(BundleContext context)
   :outertype: Activator

