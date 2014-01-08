.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.domain TestEventPayload

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework Constants

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util.jar Manifest

EventBundleIT
=============

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class EventBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EventBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EventBundleIT

getManifest
^^^^^^^^^^^

.. java:method:: @Override protected Manifest getManifest()
   :outertype: EventBundleIT

testEventListener
^^^^^^^^^^^^^^^^^

.. java:method:: public void testEventListener() throws Exception
   :outertype: EventBundleIT

testEventListener_WithAnnotation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testEventListener_WithAnnotation() throws Exception
   :outertype: EventBundleIT

testEventWithTypedPayload
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testEventWithTypedPayload() throws Exception
   :outertype: EventBundleIT

