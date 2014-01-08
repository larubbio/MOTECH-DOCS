.. java:import:: org.apache.activemq.broker.jmx QueueViewMBean

.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.admin.domain QueueMBean

.. java:import:: javax.management ObjectName

.. java:import:: java.io IOException

.. java:import:: java.util List

MBeanServiceTest
================

.. java:package:: org.motechproject.admin.jmx
   :noindex:

.. java:type:: public class MBeanServiceTest

Fields
------
mBeanServer
^^^^^^^^^^^

.. java:field:: @Mock  MotechMBeanServer mBeanServer
   :outertype: MBeanServiceTest

mBeanService
^^^^^^^^^^^^

.. java:field:: @InjectMocks  MBeanService mBeanService
   :outertype: MBeanServiceTest

Methods
-------
before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: MBeanServiceTest

shouldReturnQueuesForGivenTenant
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnQueuesForGivenTenant() throws IOException
   :outertype: MBeanServiceTest

