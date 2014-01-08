.. java:import:: org.apache.activemq ActiveMQConnectionFactory

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.springframework.jms.connection CachingConnectionFactory

.. java:import:: javax.jms Connection

.. java:import:: javax.jms JMSException

MotechCachingConnectionFactory
==============================

.. java:package:: org.motechproject.event
   :noindex:

.. java:type:: public class MotechCachingConnectionFactory extends CachingConnectionFactory

   The \ ``MotechCachingConnectionFactory``\  is used to created connection to ActiveMQ.

Methods
-------
doCreateConnection
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected Connection doCreateConnection() throws JMSException
   :outertype: MotechCachingConnectionFactory

setBrokerUrl
^^^^^^^^^^^^

.. java:method:: public void setBrokerUrl(String brokerURL)
   :outertype: MotechCachingConnectionFactory

setPassword
^^^^^^^^^^^

.. java:method:: public void setPassword(String password)
   :outertype: MotechCachingConnectionFactory

setUsername
^^^^^^^^^^^

.. java:method:: public void setUsername(String username)
   :outertype: MotechCachingConnectionFactory

