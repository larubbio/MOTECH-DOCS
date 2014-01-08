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

ServerEventRelayIT
==================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class ServerEventRelayIT

Fields
------
EXCEPTION_HANDLING_TEST
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String EXCEPTION_HANDLING_TEST
   :outertype: ServerEventRelayIT

Methods
-------
shouldNotTriggerAllListenersWhenOneListenerFails
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotTriggerAllListenersWhenOneListenerFails() throws InterruptedException, NoSuchFieldException
   :outertype: ServerEventRelayIT

shouldRedeliverMessages_SpecifiedTimes_WithDelay
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRedeliverMessages_SpecifiedTimes_WithDelay() throws InterruptedException, NoSuchFieldException
   :outertype: ServerEventRelayIT

   For the test to work, set attribute schedulerSupport="true" in the broker element of the activemq.xml Ref: http://activemq.apache.org/delay-and-schedule-message-delivery.html

teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: ServerEventRelayIT

