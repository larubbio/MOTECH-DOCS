.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages ActionType

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.admin.notification EmailNotifier

.. java:import:: org.motechproject.admin.repository AllNotificationRules

.. java:import:: org.motechproject.admin.repository AllStatusMessages

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util Comparator

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

StatusMessageServiceImpl
========================

.. java:package:: org.motechproject.admin.service.impl
   :noindex:

.. java:type:: @Service public class StatusMessageServiceImpl implements StatusMessageService

   Implementation of the \ :java:ref:`StatusMessageService`\  interface. Class provides API for everything connected with messages and notifications in admin module.

Methods
-------
critical
^^^^^^^^

.. java:method:: @Override public void critical(String text, String moduleName)
   :outertype: StatusMessageServiceImpl

critical
^^^^^^^^

.. java:method:: @Override public void critical(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageServiceImpl

debug
^^^^^

.. java:method:: @Override public void debug(String text, String moduleName)
   :outertype: StatusMessageServiceImpl

debug
^^^^^

.. java:method:: @Override public void debug(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageServiceImpl

error
^^^^^

.. java:method:: @Override public void error(String text, String moduleName)
   :outertype: StatusMessageServiceImpl

error
^^^^^

.. java:method:: @Override public void error(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageServiceImpl

getActiveMessages
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<StatusMessage> getActiveMessages()
   :outertype: StatusMessageServiceImpl

getAllMessages
^^^^^^^^^^^^^^

.. java:method:: @Override public List<StatusMessage> getAllMessages()
   :outertype: StatusMessageServiceImpl

getNotificationRules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<NotificationRule> getNotificationRules()
   :outertype: StatusMessageServiceImpl

info
^^^^

.. java:method:: @Override public void info(String text, String moduleName)
   :outertype: StatusMessageServiceImpl

info
^^^^

.. java:method:: @Override public void info(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageServiceImpl

postMessage
^^^^^^^^^^^

.. java:method:: @Override public void postMessage(StatusMessage message)
   :outertype: StatusMessageServiceImpl

postMessage
^^^^^^^^^^^

.. java:method:: @Override public void postMessage(String text, String moduleName, Level level)
   :outertype: StatusMessageServiceImpl

postMessage
^^^^^^^^^^^

.. java:method:: @Override public void postMessage(String text, String moduleName, Level level, DateTime timeout)
   :outertype: StatusMessageServiceImpl

removeMessage
^^^^^^^^^^^^^

.. java:method:: @Override public void removeMessage(StatusMessage message)
   :outertype: StatusMessageServiceImpl

removeNotificationRule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void removeNotificationRule(String id)
   :outertype: StatusMessageServiceImpl

saveNotificationRules
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void saveNotificationRules(List<NotificationRule> notificationRules)
   :outertype: StatusMessageServiceImpl

saveRule
^^^^^^^^

.. java:method:: @Override public void saveRule(NotificationRule notificationRule)
   :outertype: StatusMessageServiceImpl

warn
^^^^

.. java:method:: @Override public void warn(String text, String moduleName)
   :outertype: StatusMessageServiceImpl

warn
^^^^

.. java:method:: @Override public void warn(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageServiceImpl

