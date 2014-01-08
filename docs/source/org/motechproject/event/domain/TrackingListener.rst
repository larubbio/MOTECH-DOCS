.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

TrackingListener
================

.. java:package:: org.motechproject.event.domain
   :noindex:

.. java:type:: public class TrackingListener implements EventListener

Constructors
------------
TrackingListener
^^^^^^^^^^^^^^^^

.. java:constructor:: public TrackingListener(String identifier)
   :outertype: TrackingListener

Methods
-------
getCount
^^^^^^^^

.. java:method:: public int getCount()
   :outertype: TrackingListener

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: TrackingListener

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: TrackingListener

