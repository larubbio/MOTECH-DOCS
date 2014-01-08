.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util HashMap

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

AllAggregatedEventsIT
=====================

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllAggregatedEventsIT

Fields
------
allAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregatedEvents allAggregatedEvents
   :outertype: AllAggregatedEventsIT

Methods
-------
shouldAddNewEventToAggregation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddNewEventToAggregation()
   :outertype: AllAggregatedEventsIT

shouldFindAllAggregatedEvents
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindAllAggregatedEvents()
   :outertype: AllAggregatedEventsIT

shouldFindAllBadEvents
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindAllBadEvents()
   :outertype: AllAggregatedEventsIT

shouldFindByAggregationRule
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindByAggregationRule()
   :outertype: AllAggregatedEventsIT

shouldGroupAggregationByFieldValues
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGroupAggregationByFieldValues()
   :outertype: AllAggregatedEventsIT

shouldNotAggregateErroredEvents
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAggregateErroredEvents()
   :outertype: AllAggregatedEventsIT

shouldRemoveByAggregation
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveByAggregation()
   :outertype: AllAggregatedEventsIT

shouldRemoveByAggregationRule
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveByAggregationRule()
   :outertype: AllAggregatedEventsIT

teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: AllAggregatedEventsIT

