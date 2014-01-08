.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.eclipse.gemini.blueprint.mock MockBundle

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: org.motechproject.tasks.contract EventParameterRequest

.. java:import:: org.motechproject.tasks.contract TriggerEventRequest

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain ChannelDeregisterEvent

.. java:import:: org.motechproject.tasks.domain ChannelRegisterEvent

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.repository AllChannels

.. java:import:: org.motechproject.tasks.repository AllTasks

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.tasks.service TaskService

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework Version

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io ResourceLoader

.. java:import:: java.io ByteArrayInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net URL

.. java:import:: java.nio.charset Charset

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Properties

.. java:import:: java.util TreeSet

ChannelServiceImplTest
======================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: public class ChannelServiceImplTest

Fields
------
allChannels
^^^^^^^^^^^

.. java:field:: @Mock  AllChannels allChannels
   :outertype: ChannelServiceImplTest

bundle
^^^^^^

.. java:field:: @Mock  Bundle bundle
   :outertype: ChannelServiceImplTest

bundleContext
^^^^^^^^^^^^^

.. java:field:: @Mock  BundleContext bundleContext
   :outertype: ChannelServiceImplTest

channelService
^^^^^^^^^^^^^^

.. java:field::  ChannelService channelService
   :outertype: ChannelServiceImplTest

eventRelay
^^^^^^^^^^

.. java:field:: @Mock  EventRelay eventRelay
   :outertype: ChannelServiceImplTest

inputStream
^^^^^^^^^^^

.. java:field:: @Mock  InputStream inputStream
   :outertype: ChannelServiceImplTest

resourceLoader
^^^^^^^^^^^^^^

.. java:field:: @Mock  ResourceLoader resourceLoader
   :outertype: ChannelServiceImplTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: ChannelServiceImplTest

shouldClearAllChannels
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldClearAllChannels()
   :outertype: ChannelServiceImplTest

shouldGetAllChannels
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllChannels()
   :outertype: ChannelServiceImplTest

shouldGetChannelByChannelInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetChannelByChannelInfo()
   :outertype: ChannelServiceImplTest

shouldGetChannelIconForBundleSymbolicName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetChannelIconForBundleSymbolicName() throws IOException
   :outertype: ChannelServiceImplTest

shouldNotRegisterChannelWhenValidationExceptionIsAppeared
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterChannelWhenValidationExceptionIsAppeared()
   :outertype: ChannelServiceImplTest

shouldRaiseEventWhenChannelIsDeregistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRaiseEventWhenChannelIsDeregistered()
   :outertype: ChannelServiceImplTest

shouldRaiseEventWhenChannelIsRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRaiseEventWhenChannelIsRegistered()
   :outertype: ChannelServiceImplTest

shouldRegisterChannel
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterChannel()
   :outertype: ChannelServiceImplTest

shouldRegisterChannelFromChannelRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterChannelFromChannelRequest()
   :outertype: ChannelServiceImplTest

shouldRemoveChannelOnDeregister
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveChannelOnDeregister()
   :outertype: ChannelServiceImplTest

shouldReturnDefaultIconWhenBundleDoesNotContainIcon
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnDefaultIconWhenBundleDoesNotContainIcon() throws IOException
   :outertype: ChannelServiceImplTest

shouldReturnDefaultIconWhenBundleNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnDefaultIconWhenBundleNotFound() throws IOException
   :outertype: ChannelServiceImplTest

shouldSendEventWhenChannelWasUpdated
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventWhenChannelWasUpdated()
   :outertype: ChannelServiceImplTest

shouldThrowExceptionWhenBundleContextNotSet
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenBundleContextNotSet() throws IOException
   :outertype: ChannelServiceImplTest

