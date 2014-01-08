.. java:import:: org.apache.activemq.broker.jmx BrokerViewMBean

.. java:import:: org.apache.activemq.broker.jmx QueueViewMBean

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.management MBeanServerConnection

.. java:import:: javax.management MBeanServerInvocationHandler

.. java:import:: javax.management MalformedObjectNameException

.. java:import:: javax.management ObjectName

.. java:import:: javax.management.remote JMXConnector

.. java:import:: javax.management.remote JMXConnectorFactory

.. java:import:: javax.management.remote JMXServiceURL

.. java:import:: java.io IOException

MotechMBeanServer
=================

.. java:package:: org.motechproject.admin.jmx
   :noindex:

.. java:type:: @Component public class MotechMBeanServer

   The MBean server providing access to ActiveMQ MBeans. Uses a JMX connection.

Fields
------
DESTINATION
^^^^^^^^^^^

.. java:field:: public static final String DESTINATION
   :outertype: MotechMBeanServer

JMX_URL
^^^^^^^

.. java:field:: public static final String JMX_URL
   :outertype: MotechMBeanServer

M_BEAN_NAME
^^^^^^^^^^^

.. java:field:: public static final String M_BEAN_NAME
   :outertype: MotechMBeanServer

Constructors
------------
MotechMBeanServer
^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechMBeanServer(SettingsFacade settingsFacade)
   :outertype: MotechMBeanServer

Methods
-------
getBrokerViewMBean
^^^^^^^^^^^^^^^^^^

.. java:method:: public BrokerViewMBean getBrokerViewMBean()
   :outertype: MotechMBeanServer

   Retrieves the mbean view from the activemq broker.

   :return: a view into the broker MBeans.

getQueueViewMBean
^^^^^^^^^^^^^^^^^

.. java:method:: public QueueViewMBean getQueueViewMBean(String queueName) throws IOException
   :outertype: MotechMBeanServer

   Retrieves the MBean view for the given ActiveMQ queue.

   :param queueName: the name of the queue for which the MBean view should be retrieved.
   :return: the \ :java:ref:`QueueViewMBean`\  allowing access to queue information.

getQueueViewMBean
^^^^^^^^^^^^^^^^^

.. java:method:: public QueueViewMBean getQueueViewMBean(ObjectName name) throws IOException
   :outertype: MotechMBeanServer

   Retrieves the mbean view for the given ActiveMQ queue.

   :param name: the \ :java:ref:`ObjectName`\  representing the name of the queue for which the MBean view should be retrieved.
   :return: the \ :java:ref:`QueueViewMBean`\  allowing access to queue information.

getQueues
^^^^^^^^^

.. java:method:: public ObjectName getQueues()
   :outertype: MotechMBeanServer

   Retrieves the queue names from the ActiveMQ broker.

   :return: an array of the queue names.

