.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.ektorp BulkDeleteDocument

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support CouchDbRepositorySupport

.. java:import:: org.ektorp.support GenerateView

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MotechBaseRepository
====================

.. java:package:: org.motechproject.commons.couchdb.dao
   :noindex:

.. java:type:: public abstract class MotechBaseRepository<T extends MotechBaseDataObject> extends CouchDbRepositorySupport<T>

   Base class that all CouchDb repository classes should extend.

Constructors
------------
MotechBaseRepository
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: protected MotechBaseRepository(Class<T> type, CouchDbConnector db)
   :outertype: MotechBaseRepository

Methods
-------
addOrReplace
^^^^^^^^^^^^

.. java:method:: protected void addOrReplace(T entity, String businessFieldName, String businessId)
   :outertype: MotechBaseRepository

bulkAddOrUpdate
^^^^^^^^^^^^^^^

.. java:method:: public void bulkAddOrUpdate(List<T> records)
   :outertype: MotechBaseRepository

bulkDelete
^^^^^^^^^^

.. java:method:: public void bulkDelete(List<T> records)
   :outertype: MotechBaseRepository

getAll
^^^^^^

.. java:method:: @Override @GenerateView public List<T> getAll()
   :outertype: MotechBaseRepository

getAll
^^^^^^

.. java:method:: protected List<T> getAll(int limit)
   :outertype: MotechBaseRepository

queryViewWithKeyList
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<T> queryViewWithKeyList(String viewName, List<String> keys)
   :outertype: MotechBaseRepository

removeAll
^^^^^^^^^

.. java:method:: public void removeAll(String fieldName, String value)
   :outertype: MotechBaseRepository

removeAll
^^^^^^^^^

.. java:method:: public void removeAll()
   :outertype: MotechBaseRepository

safeRemove
^^^^^^^^^^

.. java:method:: public void safeRemove(T entity)
   :outertype: MotechBaseRepository

singleResult
^^^^^^^^^^^^

.. java:method:: protected T singleResult(List<T> resultSet)
   :outertype: MotechBaseRepository

