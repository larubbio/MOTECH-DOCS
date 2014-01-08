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

MotechEventTransformerIT
========================

.. java:package:: org.motechproject.event
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MotechEventTransformerIT

Methods
-------
teardown
^^^^^^^^

.. java:method:: @After public void teardown()
   :outertype: MotechEventTransformerIT

verifyTransformedEventHasValidId
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void verifyTransformedEventHasValidId() throws InterruptedException
   :outertype: MotechEventTransformerIT

