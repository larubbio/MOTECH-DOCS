.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util HashMap

.. java:import:: java.util Map

PeriodicDispatchEvent
=====================

.. java:package:: org.motechproject.event.aggregation.model.event
   :noindex:

.. java:type:: public class PeriodicDispatchEvent

Fields
------
SCHEDULE_JOB_ID_KEY
^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SCHEDULE_JOB_ID_KEY
   :outertype: PeriodicDispatchEvent

Constructors
------------
PeriodicDispatchEvent
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicDispatchEvent(String aggregationRuleName)
   :outertype: PeriodicDispatchEvent

PeriodicDispatchEvent
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PeriodicDispatchEvent(MotechEvent event)
   :outertype: PeriodicDispatchEvent

Methods
-------
getAggregationRuleName
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getAggregationRuleName()
   :outertype: PeriodicDispatchEvent

toMotechEvent
^^^^^^^^^^^^^

.. java:method:: public MotechEvent toMotechEvent()
   :outertype: PeriodicDispatchEvent

