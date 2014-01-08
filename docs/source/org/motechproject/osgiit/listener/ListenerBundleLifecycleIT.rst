.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework ServiceReference

ListenerBundleLifecycleIT
=========================

.. java:package:: org.motechproject.osgiit.listener
   :noindex:

.. java:type:: public class ListenerBundleLifecycleIT extends BaseOsgiIT

   Verify that event listeners are registered and cleared for a bundle. Checks that event listeners are registered and cleared properly as the motech-osgi-integration-tests bundle transitions through its life cycle.

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: ListenerBundleLifecycleIT

getTestingBundle
^^^^^^^^^^^^^^^^

.. java:method:: public Bundle getTestingBundle()
   :outertype: ListenerBundleLifecycleIT

testListenerRegistrationStopStart
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testListenerRegistrationStopStart() throws Exception
   :outertype: ListenerBundleLifecycleIT

testListenerRegistrationUninstallInstall
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testListenerRegistrationUninstallInstall() throws Exception
   :outertype: ListenerBundleLifecycleIT

