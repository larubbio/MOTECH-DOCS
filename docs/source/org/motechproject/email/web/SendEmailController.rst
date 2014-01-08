.. java:import:: org.motechproject.email.constants EmailRolesConstants

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.io IOException

SendEmailController
===================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: @Controller public class SendEmailController

   The \ ``SendEmailController``\  class is responsible for handling requests connected with sending e-mails

Constructors
------------
SendEmailController
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SendEmailController()
   :outertype: SendEmailController

SendEmailController
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SendEmailController(EmailSenderService senderService)
   :outertype: SendEmailController

Methods
-------
handleException
^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleException(Exception e) throws IOException
   :outertype: SendEmailController

sendEmail
^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseStatus public void sendEmail(Mail mail)
   :outertype: SendEmailController

