.. java:import:: org.ektorp BulkDeleteDocument

.. java:import:: org.ektorp ComplexKey

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Map

AllAggregatedEvents
===================

.. java:package:: org.motechproject.event.aggregation.repository
   :noindex:

.. java:type:: @Repository public class AllAggregatedEvents extends MotechBaseRepository<AggregatedEventRecord>

Constructors
------------
AllAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllAggregatedEvents(CouchDbConnector db)
   :outertype: AllAggregatedEvents

Methods
-------
find
^^^^

.. java:method:: @View public AggregatedEventRecord find(String aggregationRuleName, Map<String, Object> aggregationParams, Map<String, Object> nonAggregationParams)
   :outertype: AllAggregatedEvents

findAllAggregated
^^^^^^^^^^^^^^^^^

.. java:method:: public List<AggregatedEventRecord> findAllAggregated(String aggregationRuleName)
   :outertype: AllAggregatedEvents

findAllAggregations
^^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<Aggregation> findAllAggregations(String aggregationRuleName)
   :outertype: AllAggregatedEvents

findAllByErrorState
^^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<AggregatedEventRecord> findAllByErrorState(String aggregationRuleName, boolean hasError)
   :outertype: AllAggregatedEvents

findAllErrorEventsForAggregations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<Aggregation> findAllErrorEventsForAggregations(String aggregationRuleName)
   :outertype: AllAggregatedEvents

findAllErrored
^^^^^^^^^^^^^^

.. java:method:: public List<AggregatedEventRecord> findAllErrored(String aggregationRuleName)
   :outertype: AllAggregatedEvents

findByAggregationRule
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<AggregatedEventRecord> findByAggregationRule(String aggregationRuleName)
   :outertype: AllAggregatedEvents

removeByAggregation
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeByAggregation(Aggregation aggregation)
   :outertype: AllAggregatedEvents

removeByAggregationRule
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeByAggregationRule(String aggregationRule)
   :outertype: AllAggregatedEvents

