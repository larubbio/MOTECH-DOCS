OutboundEventGateway
====================

.. java:package:: org.motechproject.event
   :noindex:

.. java:type:: public interface OutboundEventGateway

Methods
-------
sendEventMessage
^^^^^^^^^^^^^^^^

.. java:method::  void sendEventMessage(MotechEvent motechEvent)
   :outertype: OutboundEventGateway

   Sends the given MotechEvent message as a payload to the message channel defined in the Spring Integration configuration file.

   :param motechEvent:

