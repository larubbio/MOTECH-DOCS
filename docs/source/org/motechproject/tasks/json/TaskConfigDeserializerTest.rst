.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.codehaus.jackson JsonFactory

.. java:import:: org.codehaus.jackson JsonParser

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.junit Assert

.. java:import:: org.junit Test

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain Filter

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain TaskConfig

.. java:import:: java.io StringWriter

.. java:import:: java.util ArrayList

.. java:import:: java.util List

TaskConfigDeserializerTest
==========================

.. java:package:: org.motechproject.tasks.json
   :noindex:

.. java:type:: public class TaskConfigDeserializerTest

Methods
-------
shouldDeserializeJsonWithFailWhenObjectNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonWithFailWhenObjectNotFound() throws Exception
   :outertype: TaskConfigDeserializerTest

shouldDeserializeJsonWithoutFailWhenObjectNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeserializeJsonWithoutFailWhenObjectNotFound() throws Exception
   :outertype: TaskConfigDeserializerTest

shouldReturnEmptyConfig
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnEmptyConfig() throws Exception
   :outertype: TaskConfigDeserializerTest

