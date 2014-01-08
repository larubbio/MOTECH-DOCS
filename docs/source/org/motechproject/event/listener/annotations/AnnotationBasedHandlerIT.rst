.. java:import:: org.junit Ignore

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.impl EventListenerRegistry

.. java:import:: org.motechproject.event.listener.impl ServerEventRelay

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util HashMap

.. java:import:: java.util Map

AnnotationBasedHandlerIT
========================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: @Ignore @RunWith @ContextConfiguration public class AnnotationBasedHandlerIT

Fields
------
eventRelay
^^^^^^^^^^

.. java:field:: @Autowired  ServerEventRelay eventRelay
   :outertype: AnnotationBasedHandlerIT

test
^^^^

.. java:field:: static boolean test
   :outertype: AnnotationBasedHandlerIT

Methods
-------
clear
^^^^^

.. java:method:: public static void clear()
   :outertype: AnnotationBasedHandlerIT

testNamedParamsHappy
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNamedParamsHappy()
   :outertype: AnnotationBasedHandlerIT

testOrderedParams
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testOrderedParams()
   :outertype: AnnotationBasedHandlerIT

testRegistry
^^^^^^^^^^^^

.. java:method:: @Test public void testRegistry()
   :outertype: AnnotationBasedHandlerIT

testRelay
^^^^^^^^^

.. java:method:: @Test public void testRelay()
   :outertype: AnnotationBasedHandlerIT

