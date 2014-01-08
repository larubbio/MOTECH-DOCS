.. java:import:: org.ektorp BulkDeleteDocument

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util List

SpringIntegrationTest
=====================

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: @RunWith public abstract class SpringIntegrationTest extends BaseUnitTest

Methods
-------
after
^^^^^

.. java:method:: @After public void after()
   :outertype: SpringIntegrationTest

before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: SpringIntegrationTest

deleteAll
^^^^^^^^^

.. java:method:: protected void deleteAll()
   :outertype: SpringIntegrationTest

getDBConnector
^^^^^^^^^^^^^^

.. java:method:: public abstract CouchDbConnector getDBConnector()
   :outertype: SpringIntegrationTest

markForDeletion
^^^^^^^^^^^^^^^

.. java:method:: protected void markForDeletion(Object... documents)
   :outertype: SpringIntegrationTest

markForDeletion
^^^^^^^^^^^^^^^

.. java:method:: protected void markForDeletion(List documents)
   :outertype: SpringIntegrationTest

markForDeletion
^^^^^^^^^^^^^^^

.. java:method:: protected void markForDeletion(Object document)
   :outertype: SpringIntegrationTest

unique
^^^^^^

.. java:method:: protected String unique(String name)
   :outertype: SpringIntegrationTest

