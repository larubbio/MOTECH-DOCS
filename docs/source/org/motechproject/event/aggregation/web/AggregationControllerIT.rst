.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRequest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

AggregationControllerIT
=======================

.. java:package:: org.motechproject.event.aggregation.web
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AggregationControllerIT

Fields
------
aggregationController
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AggregationController aggregationController
   :outertype: AggregationControllerIT

allAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregatedEvents allAggregatedEvents
   :outertype: AggregationControllerIT

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: AggregationControllerIT

shouldReturnAllAggregationsForARuleAsJson
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllAggregationsForARuleAsJson() throws Exception
   :outertype: AggregationControllerIT

shouldReturnErrorEventAggregationsForAGivenRuleAsJson
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnErrorEventAggregationsForAGivenRuleAsJson() throws Exception
   :outertype: AggregationControllerIT

teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: AggregationControllerIT

