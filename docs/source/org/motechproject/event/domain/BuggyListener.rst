.. java:import:: org.motechproject.event MotechEvent

BuggyListener
=============

.. java:package:: org.motechproject.event.domain
   :noindex:

.. java:type:: public class BuggyListener extends TrackingListener

Constructors
------------
BuggyListener
^^^^^^^^^^^^^

.. java:constructor:: public BuggyListener(int numberOfTimesExceptionThrown)
   :outertype: BuggyListener

Methods
-------
getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: BuggyListener

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: BuggyListener

