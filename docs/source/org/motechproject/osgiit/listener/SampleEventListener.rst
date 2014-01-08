.. java:import:: org.motechproject.event.listener.annotations MotechListener

SampleEventListener
===================

.. java:package:: org.motechproject.osgiit.listener
   :noindex:

.. java:type:: public class SampleEventListener

   Event listeners to be registered for integration tests, etc.

Fields
------
SUBJECT_FOR_ONE_LISTENER_A
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SUBJECT_FOR_ONE_LISTENER_A
   :outertype: SampleEventListener

SUBJECT_FOR_ONE_LISTENER_B
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SUBJECT_FOR_ONE_LISTENER_B
   :outertype: SampleEventListener

SUBJECT_FOR_TWO_LISTENERS
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SUBJECT_FOR_TWO_LISTENERS
   :outertype: SampleEventListener

Methods
-------
handleEventC
^^^^^^^^^^^^

.. java:method:: @MotechListener public void handleEventC()
   :outertype: SampleEventListener

handleEventCAlso
^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void handleEventCAlso()
   :outertype: SampleEventListener

handleEventsAB
^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void handleEventsAB()
   :outertype: SampleEventListener

