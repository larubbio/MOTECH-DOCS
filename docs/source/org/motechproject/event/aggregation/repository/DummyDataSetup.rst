.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRecord

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util Map

DummyDataSetup
==============

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class DummyDataSetup

Fields
------
allAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregatedEvents allAggregatedEvents
   :outertype: DummyDataSetup

Methods
-------
dummyData
^^^^^^^^^

.. java:method:: @Test public void dummyData()
   :outertype: DummyDataSetup

