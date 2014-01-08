.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: java.util List

StatusMessageService
====================

.. java:package:: org.motechproject.admin.service
   :noindex:

.. java:type:: public interface StatusMessageService

Methods
-------
critical
^^^^^^^^

.. java:method::  void critical(String text, String moduleName)
   :outertype: StatusMessageService

critical
^^^^^^^^

.. java:method::  void critical(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageService

debug
^^^^^

.. java:method::  void debug(String text, String moduleName)
   :outertype: StatusMessageService

debug
^^^^^

.. java:method::  void debug(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageService

error
^^^^^

.. java:method::  void error(String text, String moduleName)
   :outertype: StatusMessageService

error
^^^^^

.. java:method::  void error(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageService

getActiveMessages
^^^^^^^^^^^^^^^^^

.. java:method::  List<StatusMessage> getActiveMessages()
   :outertype: StatusMessageService

getAllMessages
^^^^^^^^^^^^^^

.. java:method::  List<StatusMessage> getAllMessages()
   :outertype: StatusMessageService

getNotificationRules
^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<NotificationRule> getNotificationRules()
   :outertype: StatusMessageService

info
^^^^

.. java:method::  void info(String text, String moduleName)
   :outertype: StatusMessageService

info
^^^^

.. java:method::  void info(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageService

postMessage
^^^^^^^^^^^

.. java:method::  void postMessage(StatusMessage message)
   :outertype: StatusMessageService

postMessage
^^^^^^^^^^^

.. java:method::  void postMessage(String text, String moduleName, Level level)
   :outertype: StatusMessageService

postMessage
^^^^^^^^^^^

.. java:method::  void postMessage(String text, String moduleName, Level level, DateTime timeout)
   :outertype: StatusMessageService

removeMessage
^^^^^^^^^^^^^

.. java:method::  void removeMessage(StatusMessage message)
   :outertype: StatusMessageService

removeNotificationRule
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void removeNotificationRule(String id)
   :outertype: StatusMessageService

saveNotificationRules
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void saveNotificationRules(List<NotificationRule> notificationRules)
   :outertype: StatusMessageService

saveRule
^^^^^^^^

.. java:method::  void saveRule(NotificationRule notificationRule)
   :outertype: StatusMessageService

warn
^^^^

.. java:method::  void warn(String text, String moduleName)
   :outertype: StatusMessageService

warn
^^^^

.. java:method::  void warn(String text, String moduleName, DateTime timeout)
   :outertype: StatusMessageService

