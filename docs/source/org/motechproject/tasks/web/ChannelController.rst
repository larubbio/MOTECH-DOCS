.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.util List

ChannelController
=================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @Controller public class ChannelController

Constructors
------------
ChannelController
^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ChannelController(ChannelService channelService)
   :outertype: ChannelController

Methods
-------
getAllChannels
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<Channel> getAllChannels()
   :outertype: ChannelController

getChannelIcon
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping public void getChannelIcon(String moduleName, HttpServletResponse response) throws IOException
   :outertype: ChannelController

