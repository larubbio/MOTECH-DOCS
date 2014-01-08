.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventResult

.. java:import:: org.motechproject.event.aggregation.model.event EventStrings

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRule

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

AggregationEvent
================

.. java:package:: org.motechproject.event.aggregation.model
   :noindex:

.. java:type:: public class AggregationEvent

Constructors
------------
AggregationEvent
^^^^^^^^^^^^^^^^

.. java:constructor:: public AggregationEvent(AggregationRule aggregationRule, Aggregation aggregation)
   :outertype: AggregationEvent

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: AggregationEvent

getAggregatedEvents
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<AggregatedEventResult> getAggregatedEvents()
   :outertype: AggregationEvent

getOriginalSubject
^^^^^^^^^^^^^^^^^^

.. java:method:: public String getOriginalSubject()
   :outertype: AggregationEvent

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: AggregationEvent

toMotechEvent
^^^^^^^^^^^^^

.. java:method:: public MotechEvent toMotechEvent()
   :outertype: AggregationEvent

