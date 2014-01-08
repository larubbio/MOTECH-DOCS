.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.springframework.mail.javamail MimeMessageHelper

.. java:import:: org.springframework.mail.javamail MimeMessagePreparator

.. java:import:: javax.mail MessagingException

.. java:import:: javax.mail.internet MimeMessage

.. java:import:: java.util Objects

MotechMimeMessagePreparator
===========================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: public class MotechMimeMessagePreparator implements MimeMessagePreparator

Constructors
------------
MotechMimeMessagePreparator
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechMimeMessagePreparator(Mail mail)
   :outertype: MotechMimeMessagePreparator

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: MotechMimeMessagePreparator

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: MotechMimeMessagePreparator

prepare
^^^^^^^

.. java:method:: @Override public void prepare(MimeMessage mimeMessage) throws MessagingException
   :outertype: MotechMimeMessagePreparator

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: MotechMimeMessagePreparator

