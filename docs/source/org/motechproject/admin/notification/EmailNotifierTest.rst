.. java:import:: org.apache.velocity.app VelocityEngine

.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.joda.time DateTime

.. java:import:: org.junit Assert

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito Mockito

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: java.util Map

EmailNotifierTest
=================

.. java:package:: org.motechproject.admin.notification
   :noindex:

.. java:type:: public class EmailNotifierTest

Fields
------
emailNotifier
^^^^^^^^^^^^^

.. java:field:: @InjectMocks  EmailNotifier emailNotifier
   :outertype: EmailNotifierTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: EmailNotifierTest

shouldJustReturnUrlPathWhenServerUrlIsNotGiven
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldJustReturnUrlPathWhenServerUrlIsNotGiven()
   :outertype: EmailNotifierTest

shouldNotAddSchemeWhenHttpIsPartOfTheUrl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAddSchemeWhenHttpIsPartOfTheUrl()
   :outertype: EmailNotifierTest

shouldSendNotification
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendNotification() throws Exception
   :outertype: EmailNotifierTest

