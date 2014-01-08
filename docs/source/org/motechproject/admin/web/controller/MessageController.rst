.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.util List

MessageController
=================

.. java:package:: org.motechproject.admin.web.controller
   :noindex:

.. java:type:: @Controller public class MessageController

Methods
-------
addRule
^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void addRule(NotificationRule notificationRule)
   :outertype: MessageController

deleteRule
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void deleteRule(String ruleId)
   :outertype: MessageController

getMessages
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<StatusMessage> getMessages(boolean all)
   :outertype: MessageController

getNotificationRules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<NotificationRule> getNotificationRules()
   :outertype: MessageController

postMessage
^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void postMessage(String text, String moduleName, String level)
   :outertype: MessageController

saveNotificationRules
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveNotificationRules(NotificationRuleDto notificationRuleDto)
   :outertype: MessageController

