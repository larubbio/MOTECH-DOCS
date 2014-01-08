.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.eventlogging.domain CouchEventLog

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

AllCouchLogsIT
==============

.. java:package:: org.motechproject.eventlogging.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllCouchLogsIT

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: AllCouchLogsIT

shouldAddAndRetrieveLogsByParameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndRetrieveLogsByParameter()
   :outertype: AllCouchLogsIT

shouldAddAndRetrieveLogsBySubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndRetrieveLogsBySubject()
   :outertype: AllCouchLogsIT

shouldAddAndRetrieveLogsBySubjectAndParameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndRetrieveLogsBySubjectAndParameter()
   :outertype: AllCouchLogsIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: AllCouchLogsIT

