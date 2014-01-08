.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain RunOnceSchedulableJob

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils IdGenerator

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util List

SchedulerBundleIT
=================

.. java:package:: org.motechproject.scheduler.osgi
   :noindex:

.. java:type:: public class SchedulerBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: SchedulerBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: SchedulerBundleIT

testRunOnceJob
^^^^^^^^^^^^^^

.. java:method:: public void testRunOnceJob() throws InterruptedException
   :outertype: SchedulerBundleIT

