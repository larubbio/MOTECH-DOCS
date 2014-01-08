.. java:import:: org.motechproject.email.constants SendEmailConstants

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

SendEmailEventHandlerImpl
=========================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: @Service public class SendEmailEventHandlerImpl

   The \ ``SendEmailEventHandlerImpl``\  class is responsible for listening to and handling events connected with sending e-mails

Constructors
------------
SendEmailEventHandlerImpl
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SendEmailEventHandlerImpl(EmailSenderService emailSenderService)
   :outertype: SendEmailEventHandlerImpl

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent event)
   :outertype: SendEmailEventHandlerImpl

