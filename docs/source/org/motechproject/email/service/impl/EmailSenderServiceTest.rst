.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailAuditService

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.springframework.mail.javamail JavaMailSender

EmailSenderServiceTest
======================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: public class EmailSenderServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: EmailSenderServiceTest

shouldSendCriticalNotification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendCriticalNotification() throws Exception
   :outertype: EmailSenderServiceTest

