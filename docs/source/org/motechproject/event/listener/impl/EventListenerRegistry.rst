.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventListenerTree

.. java:import:: org.motechproject.event.osgi MetricsServiceManager

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

.. java:import:: java.util Set

EventListenerRegistry
=====================

.. java:package:: org.motechproject.event.listener.impl
   :noindex:

.. java:type:: @Service public class EventListenerRegistry implements EventListenerRegistryService

   Implementation of {@Link EventListenerRegistryService} interface. Acts as a registry for all scheduled event listeners

Constructors
------------
EventListenerRegistry
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventListenerRegistry()
   :outertype: EventListenerRegistry

EventListenerRegistry
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventListenerRegistry(MetricsServiceManager metricsManager)
   :outertype: EventListenerRegistry

Methods
-------
clearListenersForBean
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void clearListenersForBean(String beanName)
   :outertype: EventListenerRegistry

getListenerCount
^^^^^^^^^^^^^^^^

.. java:method:: public int getListenerCount(String subject)
   :outertype: EventListenerRegistry

getListeners
^^^^^^^^^^^^

.. java:method:: public Set<EventListener> getListeners(String subject)
   :outertype: EventListenerRegistry

hasListener
^^^^^^^^^^^

.. java:method:: public boolean hasListener(String subject)
   :outertype: EventListenerRegistry

registerListener
^^^^^^^^^^^^^^^^

.. java:method:: public void registerListener(EventListener listener, List<String> subjects)
   :outertype: EventListenerRegistry

registerListener
^^^^^^^^^^^^^^^^

.. java:method:: public void registerListener(EventListener listener, String subject)
   :outertype: EventListenerRegistry

