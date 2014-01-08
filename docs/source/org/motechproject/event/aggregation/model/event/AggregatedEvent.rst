.. java:import:: org.joda.time DateTime

.. java:import:: java.util Map

AggregatedEvent
===============

.. java:package:: org.motechproject.event.aggregation.model.event
   :noindex:

.. java:type:: public interface AggregatedEvent

Methods
-------
getAggregationParams
^^^^^^^^^^^^^^^^^^^^

.. java:method::  Map<String, Object> getAggregationParams()
   :outertype: AggregatedEvent

getNonAggregationParams
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  Map<String, Object> getNonAggregationParams()
   :outertype: AggregatedEvent

getTimeStamp
^^^^^^^^^^^^

.. java:method::  DateTime getTimeStamp()
   :outertype: AggregatedEvent

