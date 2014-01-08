.. java:import:: org.motechproject.commons.api ApplicationContextServiceReferenceUtils

.. java:import:: org.motechproject.tasks.annotations TaskAnnotationBeanPostProcessor

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

BlueprintApplicationContextTracker
==================================

.. java:package:: org.motechproject.tasks.osgi
   :noindex:

.. java:type:: public class BlueprintApplicationContextTracker extends ServiceTracker

   This is effectively a bundle start/stop listener that registers/deregisters a bundle's task channel when a bundle is started/stopped respectively.

Constructors
------------
BlueprintApplicationContextTracker
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BlueprintApplicationContextTracker(BundleContext bundleContext, ChannelService channelService)
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

