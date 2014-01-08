.. java:import:: org.joda.time DateTime

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.email.domain DeliveryStatus

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.domain EmailRecords

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.motechproject.email.service EmailSenderService

.. java:import:: org.motechproject.email.service.impl EmailAuditServiceImpl

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.authority SimpleGrantedAuthority

.. java:import:: org.springframework.security.core.context SecurityContext

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.security.core.context SecurityContextImpl

.. java:import:: java.util ArrayList

.. java:import:: java.util List

EmailControllerTest
===================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: public class EmailControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: EmailControllerTest

shouldReturnGivenRecord
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnGivenRecord()
   :outertype: EmailControllerTest

shouldReturnGivenRecordAfterFiltering
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnGivenRecordAfterFiltering()
   :outertype: EmailControllerTest

shouldReturnGivenRecordAfterSorting
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnGivenRecordAfterSorting()
   :outertype: EmailControllerTest

shouldReturnProperMailsForAutoComplete
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnProperMailsForAutoComplete()
   :outertype: EmailControllerTest

shouldReturnRecordsFilteredByAddress
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnRecordsFilteredByAddress()
   :outertype: EmailControllerTest

shouldSortByDate
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSortByDate()
   :outertype: EmailControllerTest

shouldSortBySubject
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSortBySubject()
   :outertype: EmailControllerTest

