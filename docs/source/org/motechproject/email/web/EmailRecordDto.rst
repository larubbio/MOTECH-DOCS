.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: java.util Objects

EmailRecordDto
==============

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: public class EmailRecordDto extends BasicEmailRecordDto

   The \ ``EmailRecordDto``\  class represents a single Email record, as it's seen by user with full email log rights.

Constructors
------------
EmailRecordDto
^^^^^^^^^^^^^^

.. java:constructor:: public EmailRecordDto(EmailRecord record)
   :outertype: EmailRecordDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: EmailRecordDto

getFromAddress
^^^^^^^^^^^^^^

.. java:method:: public String getFromAddress()
   :outertype: EmailRecordDto

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: EmailRecordDto

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: EmailRecordDto

getToAddress
^^^^^^^^^^^^

.. java:method:: public String getToAddress()
   :outertype: EmailRecordDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: EmailRecordDto

setFromAddress
^^^^^^^^^^^^^^

.. java:method:: public void setFromAddress(String fromAddress)
   :outertype: EmailRecordDto

setMessage
^^^^^^^^^^

.. java:method:: public void setMessage(String message)
   :outertype: EmailRecordDto

setSubject
^^^^^^^^^^

.. java:method:: public void setSubject(String subject)
   :outertype: EmailRecordDto

setToAddress
^^^^^^^^^^^^

.. java:method:: public void setToAddress(String toAddress)
   :outertype: EmailRecordDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: EmailRecordDto

