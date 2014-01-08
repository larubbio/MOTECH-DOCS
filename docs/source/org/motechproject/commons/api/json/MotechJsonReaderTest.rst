.. java:import:: org.hamcrest Matchers

.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.hamcrest.core IsNull

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.commons.api.model MotechProperties

MotechJsonReaderTest
====================

.. java:package:: org.motechproject.commons.api.json
   :noindex:

.. java:type:: public class MotechJsonReaderTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: MotechJsonReaderTest

shouldFailGracefullyWhenJsonFileIsNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFailGracefullyWhenJsonFileIsNotFound()
   :outertype: MotechJsonReaderTest

shouldParseMotechProperties
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldParseMotechProperties()
   :outertype: MotechJsonReaderTest

shouldSkipMotechPropertyThatHasJsonObjectAsValue
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSkipMotechPropertyThatHasJsonObjectAsValue()
   :outertype: MotechJsonReaderTest

