.. java:import:: org.apache.http.impl.client BasicResponseHandler

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils PollingHttpClient

.. java:import:: org.motechproject.testing.utils TestContext

.. java:import:: java.io IOException

ServerBundleIT
==============

.. java:package:: org.motechproject.server.osgi.it
   :noindex:

.. java:type:: public class ServerBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: ServerBundleIT

testThatControllerIsUp
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testThatControllerIsUp() throws IOException, InterruptedException
   :outertype: ServerBundleIT

testUIFrameworkService
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testUIFrameworkService() throws IOException, InterruptedException
   :outertype: ServerBundleIT

