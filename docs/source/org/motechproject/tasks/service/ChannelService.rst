.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util List

ChannelService
==============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public interface ChannelService

   Manages CRUD operations for a \ :java:ref:`Channel`\ .

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method::  void addOrUpdate(Channel channel)
   :outertype: ChannelService

deregisterAllChannels
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void deregisterAllChannels()
   :outertype: ChannelService

deregisterChannel
^^^^^^^^^^^^^^^^^

.. java:method::  void deregisterChannel(String moduleName)
   :outertype: ChannelService

getAllChannels
^^^^^^^^^^^^^^

.. java:method::  List<Channel> getAllChannels()
   :outertype: ChannelService

getChannel
^^^^^^^^^^

.. java:method::  Channel getChannel(String moduleName)
   :outertype: ChannelService

getChannelIcon
^^^^^^^^^^^^^^

.. java:method::  BundleIcon getChannelIcon(String moduleName) throws IOException
   :outertype: ChannelService

registerChannel
^^^^^^^^^^^^^^^

.. java:method::  void registerChannel(ChannelRequest channelRequest)
   :outertype: ChannelService

registerChannel
^^^^^^^^^^^^^^^

.. java:method::  void registerChannel(InputStream stream, String moduleName, String moduleVersion)
   :outertype: ChannelService

