.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.event EventStrings

.. java:import:: org.motechproject.event.aggregation.model.event SporadicDispatchEvent

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.motechproject.event.aggregation.rule RuleAgent

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: java.util List

SporadicDispatcher
==================

.. java:package:: org.motechproject.event.aggregation.dispatch
   :noindex:

.. java:type:: public class SporadicDispatcher

Constructors
------------
SporadicDispatcher
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SporadicDispatcher(EventDispatcher eventDispatcher, AllAggregatedEvents allAggregatedEvents)
   :outertype: SporadicDispatcher

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent event)
   :outertype: SporadicDispatcher

