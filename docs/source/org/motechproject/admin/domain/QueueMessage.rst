.. java:import:: java.util Date

QueueMessage
============

.. java:package:: org.motechproject.admin.domain
   :noindex:

.. java:type:: public class QueueMessage

   Represents a message from the JMS queue.

Constructors
------------
QueueMessage
^^^^^^^^^^^^

.. java:constructor:: public QueueMessage(String messageId, Boolean redelivered, Date timestamp)
   :outertype: QueueMessage

Methods
-------
getMessageId
^^^^^^^^^^^^

.. java:method:: public String getMessageId()
   :outertype: QueueMessage

getRedelivered
^^^^^^^^^^^^^^

.. java:method:: public Boolean getRedelivered()
   :outertype: QueueMessage

getTimestamp
^^^^^^^^^^^^

.. java:method:: public String getTimestamp()
   :outertype: QueueMessage

