.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.metrics MetricsAgent

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util HashMap

MetricsIT
=========

.. java:package:: org.motechproject.metrics
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MetricsIT

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: MetricsIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown() throws Exception
   :outertype: MetricsIT

testMetricsAgent
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testMetricsAgent()
   :outertype: MetricsIT

