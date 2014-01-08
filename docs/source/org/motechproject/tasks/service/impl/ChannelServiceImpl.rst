.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain ChannelDeregisterEvent

.. java:import:: org.motechproject.tasks.domain ChannelRegisterEvent

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.json ActionEventRequestDeserializer

.. java:import:: org.motechproject.tasks.repository AllChannels

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.tasks.validation ChannelValidator

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.core.io ResourceLoader

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.lang.reflect Type

.. java:import:: java.net URL

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

ChannelServiceImpl
==================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: @Service public class ChannelServiceImpl implements ChannelService

   A \ :java:ref:`ChannelService`\ , used to manage CRUD operations for a \ :java:ref:`Channel`\  over a couchdb database.

Constructors
------------
ChannelServiceImpl
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ChannelServiceImpl(AllChannels allChannels, ResourceLoader resourceLoader, EventRelay eventRelay, IconLoader iconLoader)
   :outertype: ChannelServiceImpl

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: @Override public void addOrUpdate(Channel channel)
   :outertype: ChannelServiceImpl

deregisterAllChannels
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void deregisterAllChannels()
   :outertype: ChannelServiceImpl

deregisterChannel
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void deregisterChannel(String moduleName)
   :outertype: ChannelServiceImpl

getAllChannels
^^^^^^^^^^^^^^

.. java:method:: @Override public List<Channel> getAllChannels()
   :outertype: ChannelServiceImpl

getChannel
^^^^^^^^^^

.. java:method:: @Override public Channel getChannel(String moduleName)
   :outertype: ChannelServiceImpl

getChannelIcon
^^^^^^^^^^^^^^

.. java:method:: @Override public BundleIcon getChannelIcon(String moduleName) throws IOException
   :outertype: ChannelServiceImpl

registerChannel
^^^^^^^^^^^^^^^

.. java:method:: @Override public void registerChannel(ChannelRequest channelRequest)
   :outertype: ChannelServiceImpl

registerChannel
^^^^^^^^^^^^^^^

.. java:method:: @Override public void registerChannel(InputStream stream, String moduleName, String moduleVersion)
   :outertype: ChannelServiceImpl

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: @Autowired public void setBundleContext(BundleContext bundleContext)
   :outertype: ChannelServiceImpl

