.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.impl StdCouchDbConnector

.. java:import:: org.ektorp.impl StdCouchDbInstance

.. java:import:: org.ektorp.spring HttpClientFactoryBean

.. java:import:: org.ektorp.support GenerateView

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.motechproject.commons.couchdb.dao BusinessIdNotUniqueException

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.couchdb.service CouchDbManager

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Properties

CommonsCouchDBBundleIT.TestRepository
=====================================

.. java:package:: org.motechproject.commons.couchdb.osgi
   :noindex:

.. java:type::  class TestRepository extends MotechBaseRepository<TestRecord>
   :outertype: CommonsCouchDBBundleIT

Constructors
------------
TestRepository
^^^^^^^^^^^^^^

.. java:constructor:: protected TestRepository(Class<TestRecord> type, CouchDbConnector db)
   :outertype: CommonsCouchDBBundleIT.TestRepository

Methods
-------
addOrReplace
^^^^^^^^^^^^

.. java:method:: protected void addOrReplace(TestRecord entity)
   :outertype: CommonsCouchDBBundleIT.TestRepository

findByName
^^^^^^^^^^

.. java:method:: @GenerateView  List<TestRecord> findByName(String name)
   :outertype: CommonsCouchDBBundleIT.TestRepository

