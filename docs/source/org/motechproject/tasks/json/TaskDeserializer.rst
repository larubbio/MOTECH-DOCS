.. java:import:: org.apache.commons.beanutils BeanUtils

.. java:import:: org.codehaus.jackson JsonNode

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson ObjectCodec

.. java:import:: org.codehaus.jackson.map DeserializationContext

.. java:import:: org.codehaus.jackson.map JsonDeserializer

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.map.type TypeFactory

.. java:import:: org.codehaus.jackson.type JavaType

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskAdditionalData

.. java:import:: org.motechproject.tasks.domain TaskConfig

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io IOException

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.util Iterator

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

TaskDeserializer
================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: public class TaskDeserializer extends JsonDeserializer<Task>

Methods
-------
deserialize
^^^^^^^^^^^

.. java:method:: @Override public Task deserialize(JsonParser jsonParser, DeserializationContext deserializationContext) throws IOException
   :outertype: TaskDeserializer

