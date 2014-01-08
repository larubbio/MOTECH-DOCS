.. java:import:: org.joda.time DateTime

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.notification EmailNotifier

.. java:import:: org.motechproject.admin.repository AllNotificationRules

.. java:import:: org.motechproject.admin.repository AllStatusMessages

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.admin.service.impl StatusMessageServiceImpl

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: java.util ArrayList

.. java:import:: java.util List

StatusMessageServiceTest
========================

.. java:package:: org.motechproject.admin.messages
   :noindex:

.. java:type:: public class StatusMessageServiceTest

Fields
------
activeMessage
^^^^^^^^^^^^^

.. java:field::  StatusMessage activeMessage
   :outertype: StatusMessageServiceTest

inactiveMessage
^^^^^^^^^^^^^^^

.. java:field::  StatusMessage inactiveMessage
   :outertype: StatusMessageServiceTest

statusMessages
^^^^^^^^^^^^^^

.. java:field::  List<StatusMessage> statusMessages
   :outertype: StatusMessageServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: StatusMessageServiceTest

shouldRemoveANotificationRule
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveANotificationRule()
   :outertype: StatusMessageServiceTest

shouldReturnAllNotificationRules
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllNotificationRules()
   :outertype: StatusMessageServiceTest

shouldSaveANewRule
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveANewRule()
   :outertype: StatusMessageServiceTest

shouldSaveNotificationRules
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveNotificationRules()
   :outertype: StatusMessageServiceTest

shouldSendNotifications
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendNotifications()
   :outertype: StatusMessageServiceTest

shouldUpdateAnExistingRule
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldUpdateAnExistingRule()
   :outertype: StatusMessageServiceTest

testActiveMessages
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testActiveMessages()
   :outertype: StatusMessageServiceTest

testGetAllMessages
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetAllMessages()
   :outertype: StatusMessageServiceTest

testPostMessage
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPostMessage()
   :outertype: StatusMessageServiceTest

testPostMessageNullLevel
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPostMessageNullLevel()
   :outertype: StatusMessageServiceTest

testPostMessageNullText
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPostMessageNullText()
   :outertype: StatusMessageServiceTest

testPostMessageNullTimeout
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPostMessageNullTimeout()
   :outertype: StatusMessageServiceTest

testPostMessagePastTimeout
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testPostMessagePastTimeout()
   :outertype: StatusMessageServiceTest

testRemoveMessage
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRemoveMessage()
   :outertype: StatusMessageServiceTest

