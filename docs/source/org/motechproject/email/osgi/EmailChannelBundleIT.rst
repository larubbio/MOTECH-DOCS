.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.email.constants SendEmailConstants

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: org.subethamail.smtp.helper SimpleMessageListener

.. java:import:: org.subethamail.smtp.helper SimpleMessageListenerAdapter

.. java:import:: org.subethamail.smtp.server SMTPServer

.. java:import:: javax.mail MessagingException

.. java:import:: javax.mail Session

.. java:import:: javax.mail.internet MimeMessage

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

EmailChannelBundleIT
====================

.. java:package:: org.motechproject.email.osgi
   :noindex:

.. java:type:: public class EmailChannelBundleIT extends BaseOsgiIT implements SimpleMessageListener, WaitCondition

Methods
-------
accept
^^^^^^

.. java:method:: @Override public boolean accept(String from, String recipient)
   :outertype: EmailChannelBundleIT

deliver
^^^^^^^

.. java:method:: @Override public void deliver(String from, String recipient, InputStream data) throws IOException
   :outertype: EmailChannelBundleIT

getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EmailChannelBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EmailChannelBundleIT

needsToWait
^^^^^^^^^^^

.. java:method:: @Override public boolean needsToWait()
   :outertype: EmailChannelBundleIT

testEmailSentOnSendEmailEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testEmailSentOnSendEmailEvent() throws MessagingException, IOException, InterruptedException
   :outertype: EmailChannelBundleIT

