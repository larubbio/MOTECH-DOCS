.. java:import:: org.motechproject.admin.domain QueueMessage

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.motechproject.admin.domain QueueMBean

.. java:import:: org.motechproject.admin.jmx MBeanService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.http MediaType

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util Collections

.. java:import:: java.util List

QueueStatisticsController
=========================

.. java:package:: org.motechproject.admin.web.controller
   :noindex:

.. java:type:: @Controller public class QueueStatisticsController

Methods
-------
browse
^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<QueueMBean> browse()
   :outertype: QueueStatisticsController

getMessages
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<QueueMessage> getMessages(String queueName)
   :outertype: QueueStatisticsController

