.. java:import:: com.google.gson JsonArray

.. java:import:: com.google.gson JsonDeserializationContext

.. java:import:: com.google.gson JsonObject

.. java:import:: com.google.gson JsonParseException

.. java:import:: com.google.gson JsonPrimitive

.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: java.io IOException

.. java:import:: java.lang.reflect Type

.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

ActionEventDeserializerTest
===========================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: public class ActionEventDeserializerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: ActionEventDeserializerTest

shouldDeserializeActionEvent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeActionEvent() throws IOException
   :outertype: ActionEventDeserializerTest

shouldDeserializeActionParameters
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeActionParameters() throws IOException
   :outertype: ActionEventDeserializerTest

shouldDeserializeJsonWithActionParameters
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonWithActionParameters()
   :outertype: ActionEventDeserializerTest

shouldDeserializeJsonWithServiceInfo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonWithServiceInfo()
   :outertype: ActionEventDeserializerTest

shouldDeserializeJsonWithSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonWithSubject()
   :outertype: ActionEventDeserializerTest

shouldNotSetEmptyActionParameterSet
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSetEmptyActionParameterSet()
   :outertype: ActionEventDeserializerTest

shouldReturnNullIfJsonElementIsNotJsonObject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnNullIfJsonElementIsNotJsonObject()
   :outertype: ActionEventDeserializerTest

shouldThrowExceptionWhenSubjectAndServiceInfoAreNotExist
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenSubjectAndServiceInfoAreNotExist()
   :outertype: ActionEventDeserializerTest

