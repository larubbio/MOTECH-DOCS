.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util HashMap

.. java:import:: java.util Map

SporadicDispatchEvent
=====================

.. java:package:: org.motechproject.event.aggregation.model.event
   :noindex:

.. java:type:: public class SporadicDispatchEvent

Constructors
------------
SporadicDispatchEvent
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SporadicDispatchEvent(String aggregationRuleName, String expression)
   :outertype: SporadicDispatchEvent

SporadicDispatchEvent
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SporadicDispatchEvent(MotechEvent event)
   :outertype: SporadicDispatchEvent

Methods
-------
getAggregationRuleName
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getAggregationRuleName()
   :outertype: SporadicDispatchEvent

getExpression
^^^^^^^^^^^^^

.. java:method:: public String getExpression()
   :outertype: SporadicDispatchEvent

toMotechEvent
^^^^^^^^^^^^^

.. java:method:: public MotechEvent toMotechEvent()
   :outertype: SporadicDispatchEvent

