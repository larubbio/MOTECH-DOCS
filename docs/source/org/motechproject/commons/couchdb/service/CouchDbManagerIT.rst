.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.motechproject.commons.couchdb.service.impl CouchDbManagerImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

CouchDbManagerIT
================

.. java:package:: org.motechproject.commons.couchdb.service
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class CouchDbManagerIT

Fields
------
couchDbManager
^^^^^^^^^^^^^^

.. java:field:: @Autowired  CouchDbManagerImpl couchDbManager
   :outertype: CouchDbManagerIT

Methods
-------
testConnectorRetrieval
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testConnectorRetrieval() throws DbConnectionException
   :outertype: CouchDbManagerIT

