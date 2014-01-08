.. java:import:: org.hamcrest.text StringContains

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.domain QueueMBean

.. java:import:: org.motechproject.admin.domain QueueMessage

.. java:import:: org.motechproject.admin.jmx MBeanService

.. java:import:: org.motechproject.admin.web.controller QueueStatisticsController

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.springframework.http MediaType

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.request MockMvcRequestBuilders

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util Arrays

.. java:import:: java.util Date

QueueStatisticsControllerTest
=============================

.. java:package:: org.motechproject.admin.web
   :noindex:

.. java:type:: public class QueueStatisticsControllerTest

Fields
------
mBeanService
^^^^^^^^^^^^

.. java:field:: @Mock  MBeanService mBeanService
   :outertype: QueueStatisticsControllerTest

mockMvc
^^^^^^^

.. java:field::  MockMvc mockMvc
   :outertype: QueueStatisticsControllerTest

queueStatisticsController
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  QueueStatisticsController queueStatisticsController
   :outertype: QueueStatisticsControllerTest

tenant
^^^^^^

.. java:field:: @Mock  Tenant tenant
   :outertype: QueueStatisticsControllerTest

Methods
-------
before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: QueueStatisticsControllerTest

shouldReturnAllQueueInformation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllQueueInformation() throws Exception
   :outertype: QueueStatisticsControllerTest

shouldReturnBadRequestCodeIfQueueNameNotProvided
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnBadRequestCodeIfQueueNameNotProvided() throws Exception
   :outertype: QueueStatisticsControllerTest

shouldReturnEmptyArrayIfQueueDoesNotBelongToTenant
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnEmptyArrayIfQueueDoesNotBelongToTenant() throws Exception
   :outertype: QueueStatisticsControllerTest

shouldReturnMessageInformationGivenQueueName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnMessageInformationGivenQueueName() throws Exception
   :outertype: QueueStatisticsControllerTest

