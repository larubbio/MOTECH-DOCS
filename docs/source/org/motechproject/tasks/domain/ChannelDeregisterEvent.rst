.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.tasks.events.constants EventDataKeys

.. java:import:: org.motechproject.tasks.events.constants EventSubjects

.. java:import:: java.util HashMap

ChannelDeregisterEvent
======================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class ChannelDeregisterEvent

   A wrapper over a \ :java:ref:`MotechEvent`\  with subject {@value EventSubjects#CHANNEL_DEREGISTER_SUBJECT}. Raised when a channel is deregistered from the tasks module

Constructors
------------
ChannelDeregisterEvent
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ChannelDeregisterEvent(String moduleName)
   :outertype: ChannelDeregisterEvent

ChannelDeregisterEvent
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ChannelDeregisterEvent(MotechEvent motechEvent)
   :outertype: ChannelDeregisterEvent

Methods
-------
getChannelModuleName
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getChannelModuleName()
   :outertype: ChannelDeregisterEvent

toMotechEvent
^^^^^^^^^^^^^

.. java:method:: public MotechEvent toMotechEvent()
   :outertype: ChannelDeregisterEvent

