.. java:import:: org.junit After

.. java:import:: org.junit Assert

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.metrics.impl LoggingAgentBackendImpl

.. java:import:: org.motechproject.metrics.impl MultipleMetricsAgentImpl

.. java:import:: org.motechproject.metrics.impl StatsdAgentBackendImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

MetricsAgentBackendManagerIT
============================

.. java:package:: org.motechproject.metrics.util
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MetricsAgentBackendManagerIT

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: MetricsAgentBackendManagerIT

shouldEnableLoggingAgentOnlyByDefault
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldEnableLoggingAgentOnlyByDefault() throws Exception
   :outertype: MetricsAgentBackendManagerIT

shouldProperlyBindAndUnbindImplementations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldProperlyBindAndUnbindImplementations()
   :outertype: MetricsAgentBackendManagerIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: MetricsAgentBackendManagerIT

