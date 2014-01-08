.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.email.domain DeliveryStatus

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.repository AllEmailRecords

.. java:import:: org.motechproject.email.service EmailAuditService

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Set

EmailAuditServiceIT
===================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class EmailAuditServiceIT

Methods
-------
shouldRetrieveEmailAuditRecord
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRetrieveEmailAuditRecord()
   :outertype: EmailAuditServiceIT

shouldRetrieveEmailRecordWithSearchCriteria
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRetrieveEmailRecordWithSearchCriteria()
   :outertype: EmailAuditServiceIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: EmailAuditServiceIT

