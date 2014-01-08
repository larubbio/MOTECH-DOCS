.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api Range

.. java:import:: org.motechproject.commons.couchdb.query QueryParam

.. java:import:: org.motechproject.email.domain DeliveryStatus

.. java:import:: java.util HashSet

.. java:import:: java.util Set

EmailRecordSearchCriteria
=========================

.. java:package:: org.motechproject.email.service
   :noindex:

.. java:type:: public class EmailRecordSearchCriteria

   The \ ``EmailRecordSearchCriteria``\  class represents all criteria, that we can use to search through {@Link EmailRecord} documents in CouchDB

Methods
-------
getDeliveryStatuses
^^^^^^^^^^^^^^^^^^^

.. java:method:: public Set<String> getDeliveryStatuses()
   :outertype: EmailRecordSearchCriteria

getDeliveryTimeRange
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Range<DateTime> getDeliveryTimeRange()
   :outertype: EmailRecordSearchCriteria

getFromAddress
^^^^^^^^^^^^^^

.. java:method:: public String getFromAddress()
   :outertype: EmailRecordSearchCriteria

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: EmailRecordSearchCriteria

getQueryParam
^^^^^^^^^^^^^

.. java:method:: public QueryParam getQueryParam()
   :outertype: EmailRecordSearchCriteria

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: EmailRecordSearchCriteria

getToAddress
^^^^^^^^^^^^

.. java:method:: public String getToAddress()
   :outertype: EmailRecordSearchCriteria

withDeliveryStatuses
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withDeliveryStatuses(Set<DeliveryStatus> deliveryStatuses)
   :outertype: EmailRecordSearchCriteria

withFromAddress
^^^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withFromAddress(String fromAddress)
   :outertype: EmailRecordSearchCriteria

withMessage
^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withMessage(String message)
   :outertype: EmailRecordSearchCriteria

withMessageTime
^^^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withMessageTime(DateTime deliveryTimeRange)
   :outertype: EmailRecordSearchCriteria

withMessageTimeRange
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withMessageTimeRange(Range<DateTime> deliveryTimeRange)
   :outertype: EmailRecordSearchCriteria

withQueryParam
^^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withQueryParam(QueryParam queryParam)
   :outertype: EmailRecordSearchCriteria

withSubject
^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withSubject(String subject)
   :outertype: EmailRecordSearchCriteria

withToAddress
^^^^^^^^^^^^^

.. java:method:: public EmailRecordSearchCriteria withToAddress(String toAddress)
   :outertype: EmailRecordSearchCriteria

