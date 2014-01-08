.. java:import:: org.apache.activemq.broker.jmx QueueViewMBean

.. java:import:: org.motechproject.admin.domain QueueMBean

.. java:import:: org.motechproject.admin.domain QueueMessage

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: javax.management ObjectName

.. java:import:: javax.management.openmbean CompositeData

.. java:import:: javax.management.openmbean OpenDataException

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util List

MBeanService
============

.. java:package:: org.motechproject.admin.jmx
   :noindex:

.. java:type:: @Service public class MBeanService

   This service is responsible for retrieving JMS information through JMX. Uses an mbean server to retrieve the information.

Fields
------
DESTINATION
^^^^^^^^^^^

.. java:field:: public static final String DESTINATION
   :outertype: MBeanService

JMS_MESSAGE_ID
^^^^^^^^^^^^^^

.. java:field:: public static final String JMS_MESSAGE_ID
   :outertype: MBeanService

JMS_REDELIVERED
^^^^^^^^^^^^^^^

.. java:field:: public static final String JMS_REDELIVERED
   :outertype: MBeanService

JMS_TIMESTAMP
^^^^^^^^^^^^^

.. java:field:: public static final String JMS_TIMESTAMP
   :outertype: MBeanService

Methods
-------
getMessages
^^^^^^^^^^^

.. java:method:: public List<QueueMessage> getMessages(String queueName)
   :outertype: MBeanService

   Retrieves a list of messages for the given JMS queue.

   :param queueName: The name of the queue for which messages should be retrieved.
   :return: \ :java:ref:`List`\  of messages for the given queue.

getQueueStatistics
^^^^^^^^^^^^^^^^^^

.. java:method:: public List<QueueMBean> getQueueStatistics(String tenantId)
   :outertype: MBeanService

   Returns queue statistics for the given tenant's JMS queues. To be counted as a tenant's queue, its name must start with the tenants id.

   :param tenantId: the Id of the tenant. Statistics will be retrieved for the queues belonging to this tenant.
   :return: \ :java:ref:`List`\  of \ :java:ref:`QueueMBean`\ . One for each queue belonging to the given tenant.

