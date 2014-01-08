.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson ObjectCodec

.. java:import:: org.codehaus.jackson.map DeserializationContext

.. java:import:: org.codehaus.jackson.map JsonDeserializer

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.motechproject.tasks.domain TaskConfig

.. java:import:: org.motechproject.tasks.domain TaskConfigStep

.. java:import:: java.io IOException

.. java:import:: java.util Iterator

TaskConfigDeserializer
======================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: public class TaskConfigDeserializer extends JsonDeserializer<TaskConfig>

Methods
-------
deserialize
^^^^^^^^^^^

.. java:method:: @Override public TaskConfig deserialize(JsonParser parser, DeserializationContext context) throws IOException
   :outertype: TaskConfigDeserializer

