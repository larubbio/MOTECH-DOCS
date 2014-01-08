.. java:import:: org.hamcrest.core Is

.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event MotechEventConfig

.. java:import:: org.motechproject.event.domain BuggyListener

.. java:import:: org.motechproject.event.domain TrackingListener

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.motechproject.event.listener.impl EventListenerRegistry

.. java:import:: org.motechproject.event.listener.impl ServerEventRelay

.. java:import:: org.motechproject.testing.utils Wait

.. java:import:: org.motechproject.testing.utils WaitCondition

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ServerEventRelayIT.InvalidMessageEventListener
==============================================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type::  class InvalidMessageEventListener implements EventListener
   :outertype: ServerEventRelayIT

Methods
-------
getHandledTimes
^^^^^^^^^^^^^^^

.. java:method:: public List<DateTime> getHandledTimes()
   :outertype: ServerEventRelayIT.InvalidMessageEventListener

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: ServerEventRelayIT.InvalidMessageEventListener

getMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public MotechEvent getMotechEvent()
   :outertype: ServerEventRelayIT.InvalidMessageEventListener

handle
^^^^^^

.. java:method:: @MotechListener public synchronized void handle(MotechEvent motechEvent)
   :outertype: ServerEventRelayIT.InvalidMessageEventListener

