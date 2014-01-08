.. java:import:: java.io Serializable

.. java:import:: java.util Date

.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util UUID

MotechEvent
===========

.. java:package:: org.motechproject.event
   :noindex:

.. java:type:: public class MotechEvent implements Serializable

   Motech Scheduled Event data carrier class, Instance of this class with event specific data will be send by Motech Scheduler when a scheduled event is fired

   This class is immutable

Fields
------
EVENT_TYPE_KEY_NAME
^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String EVENT_TYPE_KEY_NAME
   :outertype: MotechEvent

PARAM_DISCARDED_MOTECH_EVENT
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PARAM_DISCARDED_MOTECH_EVENT
   :outertype: MotechEvent

PARAM_INVALID_MOTECH_EVENT
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PARAM_INVALID_MOTECH_EVENT
   :outertype: MotechEvent

PARAM_REDELIVERY_COUNT
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PARAM_REDELIVERY_COUNT
   :outertype: MotechEvent

Constructors
------------
MotechEvent
^^^^^^^^^^^

.. java:constructor:: public MotechEvent()
   :outertype: MotechEvent

MotechEvent
^^^^^^^^^^^

.. java:constructor:: public MotechEvent(String subject)
   :outertype: MotechEvent

   Constructor with subject only (parameters can be added interactively)

   :param subject: - event destination

MotechEvent
^^^^^^^^^^^

.. java:constructor:: public MotechEvent(String subject, Map<String, Object> parameters)
   :outertype: MotechEvent

   Constructor

   :param subject: - event type: Pill Reminder, Appointment Reminder ...
   :param parameters: - a Map of additional parameters

Methods
-------
copy
^^^^

.. java:method:: public MotechEvent copy(String subject, Map<String, Object> parameters)
   :outertype: MotechEvent

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: MotechEvent

getEndTime
^^^^^^^^^^

.. java:method:: public Date getEndTime()
   :outertype: MotechEvent

getId
^^^^^

.. java:method:: public UUID getId()
   :outertype: MotechEvent

getMessageRedeliveryCount
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public int getMessageRedeliveryCount()
   :outertype: MotechEvent

getParameters
^^^^^^^^^^^^^

.. java:method:: public Map<String, Object> getParameters()
   :outertype: MotechEvent

   Sets empty HashMap if parameters=null

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: MotechEvent

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: MotechEvent

incrementMessageRedeliveryCount
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void incrementMessageRedeliveryCount()
   :outertype: MotechEvent

isLastEvent
^^^^^^^^^^^

.. java:method:: public boolean isLastEvent()
   :outertype: MotechEvent

setEndTime
^^^^^^^^^^

.. java:method:: public MotechEvent setEndTime(Date endDate)
   :outertype: MotechEvent

setId
^^^^^

.. java:method:: public void setId(UUID id)
   :outertype: MotechEvent

setLastEvent
^^^^^^^^^^^^

.. java:method:: public MotechEvent setLastEvent(boolean lastEvent)
   :outertype: MotechEvent

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: MotechEvent

