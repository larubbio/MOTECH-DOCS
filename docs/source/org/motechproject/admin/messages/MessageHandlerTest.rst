.. java:import:: org.joda.time DateTime

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.admin.events EventKeys

.. java:import:: org.motechproject.admin.events EventSubjects

.. java:import:: org.motechproject.admin.listener MessageHandler

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util HashMap

.. java:import:: java.util Map

MessageHandlerTest
==================

.. java:package:: org.motechproject.admin.messages
   :noindex:

.. java:type:: public class MessageHandlerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: MessageHandlerTest

shouldPostMessageWithTimeout
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPostMessageWithTimeout()
   :outertype: MessageHandlerTest

shouldPostMessageWithoutTimeout
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPostMessageWithoutTimeout()
   :outertype: MessageHandlerTest

