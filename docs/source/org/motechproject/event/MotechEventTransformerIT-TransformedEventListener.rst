.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener.impl EventListenerRegistry

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: org.springframework.util Assert

MotechEventTransformerIT.TransformedEventListener
=================================================

.. java:package:: org.motechproject.event
   :noindex:

.. java:type::  class TransformedEventListener implements EventListener
   :outertype: MotechEventTransformerIT

Methods
-------
getEvent
^^^^^^^^

.. java:method:: public MotechEvent getEvent()
   :outertype: MotechEventTransformerIT.TransformedEventListener

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: MotechEventTransformerIT.TransformedEventListener

handle
^^^^^^

.. java:method:: @MotechListener public synchronized void handle(MotechEvent motechEvent)
   :outertype: MotechEventTransformerIT.TransformedEventListener

isEventHandled
^^^^^^^^^^^^^^

.. java:method:: public boolean isEventHandled()
   :outertype: MotechEventTransformerIT.TransformedEventListener

