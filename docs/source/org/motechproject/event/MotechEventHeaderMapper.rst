.. java:import:: org.apache.activemq ScheduledMessage

.. java:import:: org.apache.activemq.command ActiveMQObjectMessage

.. java:import:: org.apache.log4j Logger

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.integration MessageHeaders

.. java:import:: org.springframework.integration.jms DefaultJmsHeaderMapper

.. java:import:: javax.jms JMSException

.. java:import:: javax.jms Message

MotechEventHeaderMapper
=======================

.. java:package:: org.motechproject.event
   :noindex:

.. java:type:: public class MotechEventHeaderMapper extends DefaultJmsHeaderMapper

   For the delay to work, set attribute schedulerSupport="true" in the broker element of the activemq.xml Ref: http://activemq.apache.org/delay-and-schedule-message-delivery.html

Methods
-------
fromHeaders
^^^^^^^^^^^

.. java:method:: @Override public void fromHeaders(MessageHeaders messageHeaders, Message message)
   :outertype: MotechEventHeaderMapper

