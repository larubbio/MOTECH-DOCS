.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.junit.runners Parameterized

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: java.io IOException

.. java:import:: java.io StringWriter

.. java:import:: java.lang.reflect Type

.. java:import:: java.util ArrayList

.. java:import:: java.util Collection

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

ActionEventDeserializerIT
=========================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: @RunWith public class ActionEventDeserializerIT

Constructors
------------
ActionEventDeserializerIT
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionEventDeserializerIT(String path, List<ActionEventRequest> events) throws IOException
   :outertype: ActionEventDeserializerIT

Methods
-------
shouldDeserializeJson
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJson()
   :outertype: ActionEventDeserializerIT

testParameters
^^^^^^^^^^^^^^

.. java:method:: @Parameters public static Collection<Object> testParameters()
   :outertype: ActionEventDeserializerIT

