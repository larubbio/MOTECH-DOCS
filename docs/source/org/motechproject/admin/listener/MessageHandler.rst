.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.admin.events EventKeys

.. java:import:: org.motechproject.admin.events EventSubjects

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

MessageHandler
==============

.. java:package:: org.motechproject.admin.listener
   :noindex:

.. java:type:: @Component public class MessageHandler

   Event handler responsible for posting \ :java:ref:`org.motechproject.admin.domain.StatusMessage`\ s. Instead of interacting with the \ :java:ref:`StatusMessageService`\  to post status messages, modules can use Motech events. This handler is responsible for retrieving the events and posting status messages created from the event payload.

Methods
-------
messageReceived
^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void messageReceived(MotechEvent event)
   :outertype: MessageHandler

   Posts a status message using the \ :java:ref:`StatusMessageService`\ . The message is built from the event payload.

   :param event: the received event.

