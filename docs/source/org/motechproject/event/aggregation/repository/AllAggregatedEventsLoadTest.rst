.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Ignore

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRecord

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

AllAggregatedEventsLoadTest
===========================

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllAggregatedEventsLoadTest

Fields
------
allAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregatedEvents allAggregatedEvents
   :outertype: AllAggregatedEventsLoadTest

allAggregationRules
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregationRules allAggregationRules
   :outertype: AllAggregatedEventsLoadTest

db
^^

.. java:field:: @Autowired @Qualifier  CouchDbConnector db
   :outertype: AllAggregatedEventsLoadTest

Methods
-------
run
^^^

.. java:method:: @Test @Ignore public void run()
   :outertype: AllAggregatedEventsLoadTest

setup
^^^^^

.. java:method:: public void setup()
   :outertype: AllAggregatedEventsLoadTest

