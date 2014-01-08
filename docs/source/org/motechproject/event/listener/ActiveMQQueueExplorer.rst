.. java:import:: org.apache.activemq ActiveMQConnectionFactory

.. java:import:: org.apache.activemq.command ActiveMQQueue

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.jms.connection CachingConnectionFactory

.. java:import:: javax.jms Connection

.. java:import:: javax.jms JMSException

.. java:import:: javax.jms Message

.. java:import:: javax.jms MessageConsumer

.. java:import:: javax.jms QueueBrowser

.. java:import:: javax.jms Session

.. java:import:: java.util Enumeration

ActiveMQQueueExplorer
=====================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: public class ActiveMQQueueExplorer

Constructors
------------
ActiveMQQueueExplorer
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActiveMQQueueExplorer(CachingConnectionFactory connectionFactory) throws JMSException
   :outertype: ActiveMQQueueExplorer

Methods
-------
clear
^^^^^

.. java:method:: public void clear(ActiveMQQueue queue) throws JMSException
   :outertype: ActiveMQQueueExplorer

close
^^^^^

.. java:method:: public void close() throws JMSException
   :outertype: ActiveMQQueueExplorer

queueSize
^^^^^^^^^

.. java:method:: public int queueSize(ActiveMQQueue queue) throws JMSException
   :outertype: ActiveMQQueueExplorer

