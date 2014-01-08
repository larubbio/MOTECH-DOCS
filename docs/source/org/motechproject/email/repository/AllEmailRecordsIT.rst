.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeZone

.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.email.domain DeliveryStatus

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util List

AllEmailRecordsIT
=================

.. java:package:: org.motechproject.email.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllEmailRecordsIT

Methods
-------
shouldCreateEmail
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateEmail()
   :outertype: AllEmailRecordsIT

shouldCreateIdenticalMessages
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCreateIdenticalMessages()
   :outertype: AllEmailRecordsIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: AllEmailRecordsIT

