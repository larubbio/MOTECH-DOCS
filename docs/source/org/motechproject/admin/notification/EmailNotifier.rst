.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.velocity.app VelocityEngine

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: org.springframework.ui.velocity VelocityEngineUtils

.. java:import:: java.util HashMap

.. java:import:: java.util Map

EmailNotifier
=============

.. java:package:: org.motechproject.admin.notification
   :noindex:

.. java:type:: @Component public class EmailNotifier

   A component responsible for sending emails from the admin module. The sent emails are Velocity templates loaded from \ ``/mail``\  on the classpath. Uses the \ :java:ref:`EmailSenderService`\ .

Methods
-------
mergeTemplateIntoString
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  String mergeTemplateIntoString(Map<String, Object> model)
   :outertype: EmailNotifier

messagesUrl
^^^^^^^^^^^

.. java:method::  String messagesUrl()
   :outertype: EmailNotifier

send
^^^^

.. java:method:: public void send(StatusMessage statusMessage, String recipient)
   :outertype: EmailNotifier

   Sends a critical notification for a given \ :java:ref:`StatusMessage`\ .

   :param statusMessage: The \ :java:ref:`StatusMessage`\  for which the notification should be generated.
   :param recipient: The recipient of the notification.

