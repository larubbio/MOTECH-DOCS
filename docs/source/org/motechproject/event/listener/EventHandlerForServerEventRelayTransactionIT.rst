.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util Date

EventHandlerForServerEventRelayTransactionIT
============================================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: @Component public class EventHandlerForServerEventRelayTransactionIT

Fields
------
FAILING_EVENT_SUBJECT
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String FAILING_EVENT_SUBJECT
   :outertype: EventHandlerForServerEventRelayTransactionIT

LONG_RUNNING_PROCESS
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String LONG_RUNNING_PROCESS
   :outertype: EventHandlerForServerEventRelayTransactionIT

SUCCESSFUL_EVENT_SUBJECT
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SUCCESSFUL_EVENT_SUBJECT
   :outertype: EventHandlerForServerEventRelayTransactionIT

TASK_DURATION
^^^^^^^^^^^^^

.. java:field:: public static final int TASK_DURATION
   :outertype: EventHandlerForServerEventRelayTransactionIT

Methods
-------
canFail
^^^^^^^

.. java:method:: @MotechListener public void canFail(MotechEvent motechEvent)
   :outertype: EventHandlerForServerEventRelayTransactionIT

handleLongRunningProcess
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void handleLongRunningProcess(MotechEvent motechEvent) throws Exception
   :outertype: EventHandlerForServerEventRelayTransactionIT

retries
^^^^^^^

.. java:method:: public int retries()
   :outertype: EventHandlerForServerEventRelayTransactionIT

setupForFailure
^^^^^^^^^^^^^^^

.. java:method:: public EventHandlerForServerEventRelayTransactionIT setupForFailure(boolean doThrowException)
   :outertype: EventHandlerForServerEventRelayTransactionIT

wouldPass
^^^^^^^^^

.. java:method:: @MotechListener public void wouldPass(MotechEvent motechEvent)
   :outertype: EventHandlerForServerEventRelayTransactionIT

