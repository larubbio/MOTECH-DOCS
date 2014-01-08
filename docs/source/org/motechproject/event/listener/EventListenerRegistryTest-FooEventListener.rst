.. java:import:: junitx.util PrivateAccessor

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Matchers

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.impl EventListenerRegistry

.. java:import:: org.motechproject.event.osgi MetricsServiceManager

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Set

EventListenerRegistryTest.FooEventListener
==========================================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type::  class FooEventListener implements EventListener
   :outertype: EventListenerRegistryTest

Methods
-------
getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: EventListenerRegistryTest.FooEventListener

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: EventListenerRegistryTest.FooEventListener

