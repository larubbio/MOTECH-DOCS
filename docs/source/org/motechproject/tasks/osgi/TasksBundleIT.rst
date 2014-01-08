.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.server.config.service PlatformSettingsService

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.tasks.repository AllChannels

.. java:import:: org.motechproject.tasks.repository AllTaskDataProviders

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.motechproject.tasks.service TaskService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.util List

TasksBundleIT
=============

.. java:package:: org.motechproject.tasks.osgi
   :noindex:

.. java:type:: public class TasksBundleIT extends BaseOsgiIT

Fields
------
channelsLoadedOnStartup
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: static int channelsLoadedOnStartup
   :outertype: TasksBundleIT

firstTime
^^^^^^^^^

.. java:field:: static boolean firstTime
   :outertype: TasksBundleIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: TasksBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: TasksBundleIT

onSetUp
^^^^^^^

.. java:method:: @Override protected void onSetUp() throws Exception
   :outertype: TasksBundleIT

testChannelDeregistrationAndTaskDeActivationWhenBundleStops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testChannelDeregistrationAndTaskDeActivationWhenBundleStops() throws BundleException, InterruptedException
   :outertype: TasksBundleIT

testChannelRegistration
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testChannelRegistration() throws BundleException, InterruptedException
   :outertype: TasksBundleIT

testChannelService
^^^^^^^^^^^^^^^^^^

.. java:method:: public void testChannelService() throws InterruptedException
   :outertype: TasksBundleIT

testCoreServiceReferences
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testCoreServiceReferences()
   :outertype: TasksBundleIT

testDataProviderService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testDataProviderService() throws InterruptedException
   :outertype: TasksBundleIT

