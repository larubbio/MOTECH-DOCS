.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: java.lang.reflect Method

.. java:import:: java.util HashMap

.. java:import:: java.util Map

SendEmailEventHandlerImplTest
=============================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: public class SendEmailEventHandlerImplTest

Fields
------
emailEventHandler
^^^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  SendEmailEventHandlerImpl emailEventHandler
   :outertype: SendEmailEventHandlerImplTest

emailSenderService
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  EmailSenderService emailSenderService
   :outertype: SendEmailEventHandlerImplTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: SendEmailEventHandlerImplTest

testIfEmailSenderServiceIsCalledWithEventValues
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testIfEmailSenderServiceIsCalledWithEventValues()
   :outertype: SendEmailEventHandlerImplTest

testIfThereIsHandlerMethodForSendEmailEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testIfThereIsHandlerMethodForSendEmailEvent() throws NoSuchMethodException
   :outertype: SendEmailEventHandlerImplTest

