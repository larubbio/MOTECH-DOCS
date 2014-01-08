.. java:import:: org.motechproject.commons.api ApplicationContextServiceReferenceUtils

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener.annotations EventAnnotationBeanPostProcessor

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

BlueprintApplicationContextTracker
==================================

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class BlueprintApplicationContextTracker extends ServiceTracker

Constructors
------------
BlueprintApplicationContextTracker
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BlueprintApplicationContextTracker(BundleContext bundleContext, EventListenerRegistryService listenerRegistryService)
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

