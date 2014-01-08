.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.json ActionEventRequestDeserializer

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.lang.reflect Type

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashMap

.. java:import:: java.util List

AllChannelsIT
=============

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllChannelsIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: AllChannelsIT

shouldAddAndUpdateChannels
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndUpdateChannels() throws IOException
   :outertype: AllChannelsIT

shouldFindChannelByChannelInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindChannelByChannelInfo() throws Exception
   :outertype: AllChannelsIT

