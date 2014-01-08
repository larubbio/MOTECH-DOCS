.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event MotechEventConfig

.. java:import:: org.motechproject.event OutboundEventGateway

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.event.osgi MetricsServiceManager

.. java:import:: org.motechproject.event.utils MotechProxyUtils

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util Set

ServerEventRelay
================

.. java:package:: org.motechproject.event.listener.impl
   :noindex:

.. java:type:: @Component public class ServerEventRelay implements EventRelay

   This class handled incoming scheduled events and relays those events to the appropriate event listeners

Constructors
------------
ServerEventRelay
^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ServerEventRelay(OutboundEventGateway outboundEventGateway, EventListenerRegistry eventListenerRegistry, MetricsServiceManager metricsManager, MotechEventConfig motechEventConfig)
   :outertype: ServerEventRelay

Methods
-------
relayEvent
^^^^^^^^^^

.. java:method:: public void relayEvent(MotechEvent event)
   :outertype: ServerEventRelay

   Relay an event to all the listeners of that event.

   :param event: event being relayed

sendEventMessage
^^^^^^^^^^^^^^^^

.. java:method:: public void sendEventMessage(MotechEvent event)
   :outertype: ServerEventRelay

