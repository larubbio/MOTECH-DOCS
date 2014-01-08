.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson.map DeserializationContext

.. java:import:: org.codehaus.jackson.map JsonDeserializer

.. java:import:: org.codehaus.jackson.map JsonMappingException

.. java:import:: org.motechproject.email.model Mail

.. java:import:: java.io IOException

MailDeserializer
================

.. java:package:: org.motechproject.email.json
   :noindex:

.. java:type:: public class MailDeserializer extends JsonDeserializer<Mail>

Methods
-------
deserialize
^^^^^^^^^^^

.. java:method:: @Override public Mail deserialize(JsonParser jsonParser, DeserializationContext ctxt) throws IOException
   :outertype: MailDeserializer

