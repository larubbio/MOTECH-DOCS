.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.io InputStream

.. java:import:: java.lang.reflect Type

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllTaskDataProvidersIT
======================

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllTaskDataProvidersIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: AllTaskDataProvidersIT

shouldAddDataProvider
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddDataProvider()
   :outertype: AllTaskDataProvidersIT

