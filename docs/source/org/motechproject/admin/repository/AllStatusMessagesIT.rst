.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util List

AllStatusMessagesIT
===================

.. java:package:: org.motechproject.admin.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllStatusMessagesIT

Methods
-------
shouldPerformCrudOperations
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPerformCrudOperations()
   :outertype: AllStatusMessagesIT

shouldRetrieveActiveMessages
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRetrieveActiveMessages()
   :outertype: AllStatusMessagesIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: AllStatusMessagesIT

