.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages ActionType

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.admin.web.controller MessageController

.. java:import:: org.motechproject.admin.web.controller NotificationRuleDto

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: java.util List

MessageControllerTest
=====================

.. java:package:: org.motechproject.admin.web
   :noindex:

.. java:type:: public class MessageControllerTest

Fields
------
controller
^^^^^^^^^^

.. java:field:: @InjectMocks  MessageController controller
   :outertype: MessageControllerTest

statusMessageService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  StatusMessageService statusMessageService
   :outertype: MessageControllerTest

statusMessages
^^^^^^^^^^^^^^

.. java:field:: @Mock  List<StatusMessage> statusMessages
   :outertype: MessageControllerTest

uiFrameworkService
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  UIFrameworkService uiFrameworkService
   :outertype: MessageControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: MessageControllerTest

shouldAddANotificationRule
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddANotificationRule()
   :outertype: MessageControllerTest

shouldHandleNotificationDto
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldHandleNotificationDto()
   :outertype: MessageControllerTest

shouldRemoveNotificationRules
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveNotificationRules()
   :outertype: MessageControllerTest

shouldReturnNotificationRulesList
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnNotificationRulesList()
   :outertype: MessageControllerTest

testGetActiveMessagesNo
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetActiveMessagesNo()
   :outertype: MessageControllerTest

testGetAllMessages
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetAllMessages()
   :outertype: MessageControllerTest

