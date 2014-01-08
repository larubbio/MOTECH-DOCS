.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: java.util Objects

BasicEmailRecordDto
===================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: public class BasicEmailRecordDto

   The \ ``BasicEmailRecordDto``\  class represents a single Email record, as it's seen by user with basic email logging rights.

Constructors
------------
BasicEmailRecordDto
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BasicEmailRecordDto()
   :outertype: BasicEmailRecordDto

BasicEmailRecordDto
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BasicEmailRecordDto(EmailRecord record)
   :outertype: BasicEmailRecordDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: BasicEmailRecordDto

getDeliveryStatus
^^^^^^^^^^^^^^^^^

.. java:method:: public String getDeliveryStatus()
   :outertype: BasicEmailRecordDto

getDeliveryTime
^^^^^^^^^^^^^^^

.. java:method:: public String getDeliveryTime()
   :outertype: BasicEmailRecordDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: BasicEmailRecordDto

setDeliveryStatus
^^^^^^^^^^^^^^^^^

.. java:method:: public void setDeliveryStatus(String deliveryStatus)
   :outertype: BasicEmailRecordDto

setDeliveryTime
^^^^^^^^^^^^^^^

.. java:method:: public void setDeliveryTime(String deliveryTime)
   :outertype: BasicEmailRecordDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: BasicEmailRecordDto

