.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.event EventStrings

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CronBasedAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule CustomAggregationRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http MediaType

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util List

AggregationRuleControllerIT
===========================

.. java:package:: org.motechproject.event.aggregation.web
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AggregationRuleControllerIT

Fields
------
aggregationRuleController
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AggregationRuleController aggregationRuleController
   :outertype: AggregationRuleControllerIT

allAggregationRules
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregationRules allAggregationRules
   :outertype: AggregationRuleControllerIT

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: AggregationRuleControllerIT

shouldCreateARule
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateARule() throws Exception
   :outertype: AggregationRuleControllerIT

shouldDeleteAnExistingRule
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteAnExistingRule() throws Exception
   :outertype: AggregationRuleControllerIT

shouldReplaceAnExistingRule
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReplaceAnExistingRule() throws Exception
   :outertype: AggregationRuleControllerIT

shouldReturnASingleRuleByNameAsJson
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnASingleRuleByNameAsJson() throws Exception
   :outertype: AggregationRuleControllerIT

shouldReturnAllRulesAsJson
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllRulesAsJson() throws Exception
   :outertype: AggregationRuleControllerIT

shouldReturnHttp400ForBadJson
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnHttp400ForBadJson() throws Exception
   :outertype: AggregationRuleControllerIT

shouldValidateNestedFields
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateNestedFields() throws Exception
   :outertype: AggregationRuleControllerIT

shouldValidateRequestFields
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateRequestFields() throws Exception
   :outertype: AggregationRuleControllerIT

teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: AggregationRuleControllerIT

