.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.tasks.events.constants EventDataKeys

.. java:import:: org.motechproject.tasks.events.constants EventSubjects

.. java:import:: java.util HashMap

ChannelRegisterEvent
====================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class ChannelRegisterEvent

   A wrapper over a \ :java:ref:`MotechEvent`\  with subject {@value EventSubjects#CHANNEL_REGISTER_SUBJECT}. Raised when a channel is registered with the tasks module

Constructors
------------
ChannelRegisterEvent
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ChannelRegisterEvent(String moduleName)
   :outertype: ChannelRegisterEvent

ChannelRegisterEvent
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ChannelRegisterEvent(MotechEvent motechEvent)
   :outertype: ChannelRegisterEvent

Methods
-------
getChannelModuleName
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getChannelModuleName()
   :outertype: ChannelRegisterEvent

toMotechEvent
^^^^^^^^^^^^^

.. java:method:: public MotechEvent toMotechEvent()
   :outertype: ChannelRegisterEvent

