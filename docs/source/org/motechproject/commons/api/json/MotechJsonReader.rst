.. java:import:: com.google.gson Gson

.. java:import:: com.google.gson GsonBuilder

.. java:import:: com.google.gson JsonDeserializationContext

.. java:import:: com.google.gson JsonDeserializer

.. java:import:: com.google.gson JsonElement

.. java:import:: com.google.gson JsonIOException

.. java:import:: com.google.gson JsonObject

.. java:import:: com.google.gson JsonParseException

.. java:import:: com.google.gson JsonPrimitive

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.joda.time LocalDate

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.commons.api.model MotechProperties

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.lang.reflect Type

.. java:import:: java.text ParseException

.. java:import:: java.text SimpleDateFormat

.. java:import:: java.util Date

.. java:import:: java.util HashMap

.. java:import:: java.util Map

MotechJsonReader
================

.. java:package:: org.motechproject.commons.api.json
   :noindex:

.. java:type:: public class MotechJsonReader

Methods
-------
readFromFile
^^^^^^^^^^^^

.. java:method:: public Object readFromFile(String classpathFile, Type ofType)
   :outertype: MotechJsonReader

readFromStream
^^^^^^^^^^^^^^

.. java:method:: public Object readFromStream(InputStream stream, Type ofType)
   :outertype: MotechJsonReader

readFromString
^^^^^^^^^^^^^^

.. java:method:: public Object readFromString(String text, Type ofType)
   :outertype: MotechJsonReader

readFromString
^^^^^^^^^^^^^^

.. java:method:: public Object readFromString(String text, Type ofType, Map<Type, Object> typeAdapters)
   :outertype: MotechJsonReader

