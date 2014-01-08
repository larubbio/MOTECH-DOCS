.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util Arrays

.. java:import:: java.util List

EventHandlerAnnotationProcessorBundleIT
=======================================

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class EventHandlerAnnotationProcessorBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EventHandlerAnnotationProcessorBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EventHandlerAnnotationProcessorBundleIT

testThatBeansWithMotechListenerAnnotationsAreBeingRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatBeansWithMotechListenerAnnotationsAreBeingRegistered() throws InterruptedException
   :outertype: EventHandlerAnnotationProcessorBundleIT

