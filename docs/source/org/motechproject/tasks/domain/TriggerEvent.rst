.. java:import:: org.motechproject.tasks.contract EventParameterRequest

.. java:import:: org.motechproject.tasks.contract TriggerEventRequest

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Objects

TriggerEvent
============

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class TriggerEvent extends TaskEvent

   The \ ``TriggerEvent``\  class is responsible for storing data about event

Constructors
------------
TriggerEvent
^^^^^^^^^^^^

.. java:constructor:: public TriggerEvent()
   :outertype: TriggerEvent

TriggerEvent
^^^^^^^^^^^^

.. java:constructor:: public TriggerEvent(String displayName, String subject, String description, List<EventParameter> eventParameters)
   :outertype: TriggerEvent

TriggerEvent
^^^^^^^^^^^^

.. java:constructor:: public TriggerEvent(TriggerEventRequest triggerEventRequest)
   :outertype: TriggerEvent

Methods
-------
containsParameter
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean containsParameter(String key)
   :outertype: TriggerEvent

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TriggerEvent

getEventParameters
^^^^^^^^^^^^^^^^^^

.. java:method:: public List<EventParameter> getEventParameters()
   :outertype: TriggerEvent

getKeyType
^^^^^^^^^^

.. java:method:: public String getKeyType(String key)
   :outertype: TriggerEvent

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TriggerEvent

setEventParameters
^^^^^^^^^^^^^^^^^^

.. java:method:: public void setEventParameters(List<EventParameter> eventParameters)
   :outertype: TriggerEvent

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TriggerEvent

