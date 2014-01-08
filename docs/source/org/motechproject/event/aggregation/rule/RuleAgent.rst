.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEvent

.. java:import:: org.mvel MVEL

.. java:import:: java.util List

RuleAgent
=========

.. java:package:: org.motechproject.event.aggregation.rule
   :noindex:

.. java:type:: public class RuleAgent

Constructors
------------
RuleAgent
^^^^^^^^^

.. java:constructor:: public RuleAgent(String dispatchRule, List<? extends AggregatedEvent> events)
   :outertype: RuleAgent

Methods
-------
execute
^^^^^^^

.. java:method:: public boolean execute()
   :outertype: RuleAgent

getEvents
^^^^^^^^^

.. java:method:: public List<? extends AggregatedEvent> getEvents()
   :outertype: RuleAgent

getFirstEvent
^^^^^^^^^^^^^

.. java:method:: public AggregatedEvent getFirstEvent()
   :outertype: RuleAgent

getLastEvent
^^^^^^^^^^^^

.. java:method:: public AggregatedEvent getLastEvent()
   :outertype: RuleAgent

getNow
^^^^^^

.. java:method:: public DateTime getNow()
   :outertype: RuleAgent

