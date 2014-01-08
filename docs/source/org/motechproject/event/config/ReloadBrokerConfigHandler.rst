.. java:import:: org.motechproject.event MotechCachingConnectionFactory

.. java:import:: org.osgi.service.event Event

.. java:import:: org.osgi.service.event EventHandler

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: javax.jms JMSException

ReloadBrokerConfigHandler
=========================

.. java:package:: org.motechproject.event.config
   :noindex:

.. java:type:: public class ReloadBrokerConfigHandler implements EventHandler

   The \ ``ReloadBrokerConfigHandler``\  handles changes in the activemq broker.url variable.

Constructors
------------
ReloadBrokerConfigHandler
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ReloadBrokerConfigHandler(MotechCachingConnectionFactory connectionFactory)
   :outertype: ReloadBrokerConfigHandler

Methods
-------
handleEvent
^^^^^^^^^^^

.. java:method:: @Override public void handleEvent(Event event)
   :outertype: ReloadBrokerConfigHandler

