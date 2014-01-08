.. java:import:: org.motechproject.server.api BundleLoadingException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: java.io IOException

.. java:import:: java.util List

BlueprintApplicationContextTracker
==================================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class BlueprintApplicationContextTracker extends ServiceTracker

   The \ ``BlueprintApplicationContextTracker``\  class tracks application contexts, which are registered as services.

Constructors
------------
BlueprintApplicationContextTracker
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BlueprintApplicationContextTracker(BundleContext context)
   :outertype: BlueprintApplicationContextTracker

Methods
-------
addingService
^^^^^^^^^^^^^

.. java:method:: @Override public Object addingService(ServiceReference serviceReference)
   :outertype: BlueprintApplicationContextTracker

removedService
^^^^^^^^^^^^^^

.. java:method:: @Override public void removedService(ServiceReference reference, Object service)
   :outertype: BlueprintApplicationContextTracker

