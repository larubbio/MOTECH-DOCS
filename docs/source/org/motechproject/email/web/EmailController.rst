.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.commons.api CsvConverter

.. java:import:: org.motechproject.commons.api Range

.. java:import:: org.motechproject.email.constants EmailRolesConstants

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.domain EmailRecordComparator

.. java:import:: org.motechproject.email.domain EmailRecords

.. java:import:: org.motechproject.email.service EmailAuditService

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.authority SimpleGrantedAuthority

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

EmailController
===============

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: @Controller public class EmailController

   The \ ``EmailController``\  class is used by view layer for getting information about all {@Link EmailRecords} or single {@Link EmailRecord}. It stores the most recent records and allows filtering and sorting them by given criteria.

Methods
-------
exportEmailLog
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize public void exportEmailLog(String range, String month, HttpServletResponse response) throws IOException
   :outertype: EmailController

getAvailableMails
^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseBody public List<String> getAvailableMails(String autoComplete, String partialAddress)
   :outertype: EmailController

getAvailableMonths
^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseBody public List<String> getAvailableMonths()
   :outertype: EmailController

getEmail
^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseBody public EmailRecords getEmail(int mailid)
   :outertype: EmailController

getEmails
^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseBody public EmailRecords getEmails(GridSettings filter)
   :outertype: EmailController

