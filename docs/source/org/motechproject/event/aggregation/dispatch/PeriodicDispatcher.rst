.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.event EventStrings

.. java:import:: org.motechproject.event.aggregation.model.event PeriodicDispatchEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

PeriodicDispatcher
==================

.. java:package:: org.motechproject.event.aggregation.dispatch
   :noindex:

.. java:type:: @Component public class PeriodicDispatcher

Constructors
------------
PeriodicDispatcher
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public PeriodicDispatcher(EventDispatcher eventDispatcher)
   :outertype: PeriodicDispatcher

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent event)
   :outertype: PeriodicDispatcher

