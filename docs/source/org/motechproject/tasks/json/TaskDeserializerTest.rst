.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.codehaus.jackson JsonFactory

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.junit Assert

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.junit.runners Parameterized

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: java.io IOException

.. java:import:: java.io StringWriter

.. java:import:: java.util ArrayList

.. java:import:: java.util Collection

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

TaskDeserializerTest
====================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: @RunWith public class TaskDeserializerTest

Constructors
------------
TaskDeserializerTest
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDeserializerTest(String path) throws IOException
   :outertype: TaskDeserializerTest

Methods
-------
shouldDeserializeJson
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJson() throws IOException
   :outertype: TaskDeserializerTest

testParameters
^^^^^^^^^^^^^^

.. java:method:: @Parameters public static Collection<Object> testParameters()
   :outertype: TaskDeserializerTest

