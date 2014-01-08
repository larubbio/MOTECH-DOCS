.. java:import:: org.apache.http HttpStatus

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.node ObjectNode

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.springframework.http MediaType

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

SendEmailControllerTest
=======================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: public class SendEmailControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: SendEmailControllerTest

shouldExecuteSendEmailRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldExecuteSendEmailRequest() throws Exception
   :outertype: SendEmailControllerTest

shouldHandleExceptionDuringExecutionSendEmailRequest
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldHandleExceptionDuringExecutionSendEmailRequest() throws Exception
   :outertype: SendEmailControllerTest

shouldSendEmail
^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEmail() throws Exception
   :outertype: SendEmailControllerTest

