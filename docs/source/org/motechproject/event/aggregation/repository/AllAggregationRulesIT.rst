.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllAggregationRulesIT
=====================

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllAggregationRulesIT

Fields
------
allAggregationRules
^^^^^^^^^^^^^^^^^^^

.. java:field:: @Autowired  AllAggregationRules allAggregationRules
   :outertype: AllAggregationRulesIT

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup()
   :outertype: AllAggregationRulesIT

shouldAddAndFindRuleByName
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndFindRuleByName()
   :outertype: AllAggregationRulesIT

shouldRemoveExistingRule
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveExistingRule()
   :outertype: AllAggregationRulesIT

shouldReplaceExistingRule
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReplaceExistingRule()
   :outertype: AllAggregationRulesIT

teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: AllAggregationRulesIT

