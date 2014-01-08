.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: java.util Objects

EmailRecord
===========

.. java:package:: org.motechproject.email.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class EmailRecord extends MotechBaseDataObject

   The \ ``EmailRecord``\  class represents a single Email record stored in CouchDB

Constructors
------------
EmailRecord
^^^^^^^^^^^

.. java:constructor:: public EmailRecord()
   :outertype: EmailRecord

EmailRecord
^^^^^^^^^^^

.. java:constructor:: public EmailRecord(String fromAddress, String toAddress, String subject, String message, DateTime deliveryTime, DeliveryStatus deliveryStatus)
   :outertype: EmailRecord

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: EmailRecord

getDeliveryStatus
^^^^^^^^^^^^^^^^^

.. java:method:: public DeliveryStatus getDeliveryStatus()
   :outertype: EmailRecord

getDeliveryTime
^^^^^^^^^^^^^^^

.. java:method:: public DateTime getDeliveryTime()
   :outertype: EmailRecord

getFromAddress
^^^^^^^^^^^^^^

.. java:method:: public String getFromAddress()
   :outertype: EmailRecord

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: EmailRecord

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: EmailRecord

getToAddress
^^^^^^^^^^^^

.. java:method:: public String getToAddress()
   :outertype: EmailRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: EmailRecord

setFromAddress
^^^^^^^^^^^^^^

.. java:method:: public void setFromAddress(String fromAddress)
   :outertype: EmailRecord

setMessage
^^^^^^^^^^

.. java:method:: public void setMessage(String message)
   :outertype: EmailRecord

setSubject
^^^^^^^^^^

.. java:method:: public void setSubject(String subject)
   :outertype: EmailRecord

setToAddress
^^^^^^^^^^^^

.. java:method:: public void setToAddress(String toAddress)
   :outertype: EmailRecord

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: EmailRecord

