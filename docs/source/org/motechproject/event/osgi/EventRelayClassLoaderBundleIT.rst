.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Properties

EventRelayClassLoaderBundleIT
=============================

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class EventRelayClassLoaderBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EventRelayClassLoaderBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EventRelayClassLoaderBundleIT

testThatEventHandlerClassLoaderIsInvokedWithCurrentClassLoaderSetAsEventRelaysClassLoader
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatEventHandlerClassLoaderIsInvokedWithCurrentClassLoaderSetAsEventRelaysClassLoader() throws InterruptedException
   :outertype: EventRelayClassLoaderBundleIT

