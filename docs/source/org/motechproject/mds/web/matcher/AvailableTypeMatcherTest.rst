.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.mds.dto AvailableTypeDto

.. java:import:: org.motechproject.mds.web ExampleData

.. java:import:: org.springframework.context MessageSource

.. java:import:: java.util List

AvailableTypeMatcherTest
========================

.. java:package:: org.motechproject.mds.web.matcher
   :noindex:

.. java:type:: public class AvailableTypeMatcherTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: AvailableTypeMatcherTest

shouldMatchAllTypesIfTermIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldMatchAllTypesIfTermIsBlank() throws Exception
   :outertype: AvailableTypeMatcherTest

shouldMatchTypeByDisplayName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldMatchTypeByDisplayName() throws Exception
   :outertype: AvailableTypeMatcherTest

shouldNotMatchTypeByDisplayName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotMatchTypeByDisplayName() throws Exception
   :outertype: AvailableTypeMatcherTest

