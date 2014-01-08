.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.motechproject.email.model Mail

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.subethamail.wiser Wiser

.. java:import:: org.subethamail.wiser WiserMessage

.. java:import:: javax.mail MessagingException

.. java:import:: java.io IOException

.. java:import:: java.util List

EmailBundleIT
=============

.. java:package:: org.motechproject.email.osgi
   :noindex:

.. java:type:: public class EmailBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EmailBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EmailBundleIT

onSetUp
^^^^^^^

.. java:method:: @Before public void onSetUp()
   :outertype: EmailBundleIT

onTearDown
^^^^^^^^^^

.. java:method:: @After public void onTearDown()
   :outertype: EmailBundleIT

testEmailService
^^^^^^^^^^^^^^^^

.. java:method:: public void testEmailService() throws MessagingException, IOException
   :outertype: EmailBundleIT

