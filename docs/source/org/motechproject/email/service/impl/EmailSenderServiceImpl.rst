.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.email.domain DeliveryStatus

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailAuditService

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.mail MailException

.. java:import:: org.springframework.mail.javamail JavaMailSender

.. java:import:: org.springframework.stereotype Service

EmailSenderServiceImpl
======================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: @Service public class EmailSenderServiceImpl implements EmailSenderService

   The \ ``EmailSenderServiceImpl``\  class provides API for sending e-mails

Methods
-------
getMimeMessagePreparator
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  MotechMimeMessagePreparator getMimeMessagePreparator(Mail mail)
   :outertype: EmailSenderServiceImpl

send
^^^^

.. java:method:: @Override public void send(Mail mail)
   :outertype: EmailSenderServiceImpl

