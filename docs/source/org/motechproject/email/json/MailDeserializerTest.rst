.. java:import:: org.codehaus.jackson JsonFactory

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson.map JsonMappingException

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.node ObjectNode

.. java:import:: org.junit Test

.. java:import:: org.motechproject.email.model Mail

.. java:import:: java.io IOException

MailDeserializerTest
====================

.. java:package:: org.motechproject.email.json
   :noindex:

.. java:type:: public class MailDeserializerTest

Methods
-------
shouldDeserializeJsonToMailObject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonToMailObject() throws Exception
   :outertype: MailDeserializerTest

shouldThrowExceptionWhenFromAddressFieldIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenFromAddressFieldIsBlank() throws Exception
   :outertype: MailDeserializerTest

shouldThrowExceptionWhenSubjectFieldIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenSubjectFieldIsBlank() throws Exception
   :outertype: MailDeserializerTest

shouldThrowExceptionWhenTextFieldIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenTextFieldIsBlank() throws Exception
   :outertype: MailDeserializerTest

shouldThrowExceptionWhenToAddressFieldIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenToAddressFieldIsBlank() throws Exception
   :outertype: MailDeserializerTest

