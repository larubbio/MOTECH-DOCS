.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: javax.servlet ServletOutputStream

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ChannelControllerTest
=====================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: public class ChannelControllerTest

Fields
------
channelService
^^^^^^^^^^^^^^

.. java:field:: @Mock  ChannelService channelService
   :outertype: ChannelControllerTest

controller
^^^^^^^^^^

.. java:field::  ChannelController controller
   :outertype: ChannelControllerTest

outputStream
^^^^^^^^^^^^

.. java:field:: @Mock  ServletOutputStream outputStream
   :outertype: ChannelControllerTest

response
^^^^^^^^

.. java:field:: @Mock  HttpServletResponse response
   :outertype: ChannelControllerTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: ChannelControllerTest

shouldGetAllChannels
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllChannels()
   :outertype: ChannelControllerTest

shouldGetChannelIcon
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetChannelIcon() throws IOException
   :outertype: ChannelControllerTest

