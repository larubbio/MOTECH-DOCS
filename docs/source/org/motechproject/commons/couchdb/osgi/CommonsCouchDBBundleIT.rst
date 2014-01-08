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

CommonsCouchDBBundleIT
======================

.. java:package:: org.motechproject.commons.couchdb.osgi
   :noindex:

.. java:type:: public class CommonsCouchDBBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: CommonsCouchDBBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: CommonsCouchDBBundleIT

testCommonsCouchDB
^^^^^^^^^^^^^^^^^^

.. java:method:: public void testCommonsCouchDB() throws Exception
   :outertype: CommonsCouchDBBundleIT

testCouchDbManager
^^^^^^^^^^^^^^^^^^

.. java:method:: public void testCouchDbManager() throws Exception
   :outertype: CommonsCouchDBBundleIT

