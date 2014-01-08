.. java:import:: org.apache.log4j Level

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllLogMappingsIT
================

.. java:package:: org.motechproject.osgi.web.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllLogMappingsIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: AllLogMappingsIT

testAddOrUpdate
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testAddOrUpdate() throws Exception
   :outertype: AllLogMappingsIT

testByLogName
^^^^^^^^^^^^^

.. java:method:: @Test public void testByLogName() throws Exception
   :outertype: AllLogMappingsIT

testRemoveByLogName
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRemoveByLogName() throws Exception
   :outertype: AllLogMappingsIT

