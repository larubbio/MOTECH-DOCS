.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.motechproject.event.listener.annotations MotechListenerType

.. java:import:: org.motechproject.event.listener.annotations MotechParam

.. java:import:: org.springframework.stereotype Component

.. java:import:: org.springframework.util Assert

.. java:import:: java.io InputStream

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

.. java:import:: java.util Properties

TestHandler
===========

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: @Component public class TestHandler

Fields
------
EVENTS_HANDLED
^^^^^^^^^^^^^^

.. java:field:: public static final List<String> EVENTS_HANDLED
   :outertype: TestHandler

PROPERTIES
^^^^^^^^^^

.. java:field:: public static final Properties PROPERTIES
   :outertype: TestHandler

SUBJECT_READ
^^^^^^^^^^^^

.. java:field:: public static final String SUBJECT_READ
   :outertype: TestHandler

TEST_SUBJECT
^^^^^^^^^^^^

.. java:field:: public static final String TEST_SUBJECT
   :outertype: TestHandler

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent event)
   :outertype: TestHandler

handleParams
^^^^^^^^^^^^

.. java:method:: @MotechListener public void handleParams(Integer a, Integer b, String s)
   :outertype: TestHandler

handleX
^^^^^^^

.. java:method:: @MotechListener public void handleX(MotechEvent event)
   :outertype: TestHandler

handleY
^^^^^^^

.. java:method:: @MotechListener public void handleY(MotechEvent event)
   :outertype: TestHandler

namedParams
^^^^^^^^^^^

.. java:method:: @MotechListener public void namedParams(String id, String key)
   :outertype: TestHandler

orderedParams
^^^^^^^^^^^^^

.. java:method:: @MotechListener public void orderedParams(Integer a, Integer b, String s)
   :outertype: TestHandler

read
^^^^

.. java:method:: @MotechListener public void read(MotechEvent event)
   :outertype: TestHandler

