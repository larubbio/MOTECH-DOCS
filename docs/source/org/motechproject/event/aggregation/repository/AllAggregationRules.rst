.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support GenerateView

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRecord

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

AllAggregationRules
===================

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @Repository public class AllAggregationRules extends MotechBaseRepository<AggregationRuleRecord>

Constructors
------------
AllAggregationRules
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllAggregationRules(CouchDbConnector db)
   :outertype: AllAggregationRules

Methods
-------
addOrReplace
^^^^^^^^^^^^

.. java:method:: public void addOrReplace(AggregationRuleRecord rule)
   :outertype: AllAggregationRules

findByName
^^^^^^^^^^

.. java:method:: @GenerateView public AggregationRuleRecord findByName(String name)
   :outertype: AllAggregationRules

remove
^^^^^^

.. java:method:: public void remove(String ruleName)
   :outertype: AllAggregationRules

