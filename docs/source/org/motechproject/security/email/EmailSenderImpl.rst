.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.velocity.app VelocityEngine

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context.support ResourceBundleMessageSource

.. java:import:: org.springframework.stereotype Service

.. java:import:: org.springframework.ui.velocity VelocityEngineUtils

.. java:import:: java.util HashMap

.. java:import:: java.util Map

EmailSenderImpl
===============

.. java:package:: org.motechproject.security.email
   :noindex:

.. java:type:: @Service public class EmailSenderImpl implements EmailSender

   Implementation of the \ :java:ref:`EmailSender`\  interface. Class provides API for sending e-mails

Methods
-------
sendLoginInfo
^^^^^^^^^^^^^

.. java:method:: public void sendLoginInfo(MotechUser user, String password)
   :outertype: EmailSenderImpl

sendOneTimeToken
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void sendOneTimeToken(PasswordRecovery recovery)
   :outertype: EmailSenderImpl

sendResecoveryEmail
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void sendResecoveryEmail(PasswordRecovery recovery)
   :outertype: EmailSenderImpl

