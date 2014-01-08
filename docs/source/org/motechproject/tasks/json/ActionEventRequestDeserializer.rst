.. java:import:: com.google.gson JsonArray

.. java:import:: com.google.gson JsonDeserializationContext

.. java:import:: com.google.gson JsonDeserializer

.. java:import:: com.google.gson JsonElement

.. java:import:: com.google.gson JsonObject

.. java:import:: com.google.gson JsonParseException

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: java.lang.reflect Type

ActionEventRequestDeserializer
==============================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: public class ActionEventRequestDeserializer implements JsonDeserializer<ActionEventRequest>

Fields
------
ACTION_PARAMETERS_FIELD
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String ACTION_PARAMETERS_FIELD
   :outertype: ActionEventRequestDeserializer

DESCRIPTION_FIELD
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DESCRIPTION_FIELD
   :outertype: ActionEventRequestDeserializer

DISPLAY_NAME_FIELD
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DISPLAY_NAME_FIELD
   :outertype: ActionEventRequestDeserializer

SERVICE_INTERFACE_FIELD
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SERVICE_INTERFACE_FIELD
   :outertype: ActionEventRequestDeserializer

SERVICE_METHOD_FIELD
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SERVICE_METHOD_FIELD
   :outertype: ActionEventRequestDeserializer

SUBJECT_FIELD
^^^^^^^^^^^^^

.. java:field:: public static final String SUBJECT_FIELD
   :outertype: ActionEventRequestDeserializer

Methods
-------
deserialize
^^^^^^^^^^^

.. java:method:: @Override public ActionEventRequest deserialize(JsonElement element, Type type, JsonDeserializationContext context)
   :outertype: ActionEventRequestDeserializer

