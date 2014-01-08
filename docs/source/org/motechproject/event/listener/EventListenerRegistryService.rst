.. java:import:: java.util List

.. java:import:: java.util Set

EventListenerRegistryService
============================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: public interface EventListenerRegistryService

   This interface is necessary for OSGi service publication. The implementing class acts as a registry for all scheduled event listeners. One can register themselves to listen for a specific set of event types.

Methods
-------
clearListenersForBean
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void clearListenersForBean(String beanName)
   :outertype: EventListenerRegistryService

   This method is responsible for removing listeners for a particular bean. This is necessary when bundles are stopped in some fashion so that the listener does not persist.

   :param beanName: The bean name from the Spring context of the candidate class for listener clearing

getListenerCount
^^^^^^^^^^^^^^^^

.. java:method::  int getListenerCount(String subject)
   :outertype: EventListenerRegistryService

   Get the count of listeners for a particular subject.

   :param subject:

getListeners
^^^^^^^^^^^^

.. java:method::  Set<EventListener> getListeners(String subject)
   :outertype: EventListenerRegistryService

   Retrieve a list of event listeners for a given event type. If there are no listeners, an empty list is returned.

   :param subject: The event type that you are seeking listeners for
   :return: A list of scheduled event listeners that are interested in that event

hasListener
^^^^^^^^^^^

.. java:method::  boolean hasListener(String subject)
   :outertype: EventListenerRegistryService

   See if a particular subject has any listeners.

   :param subject:

registerListener
^^^^^^^^^^^^^^^^

.. java:method::  void registerListener(EventListener listener, List<String> subjects)
   :outertype: EventListenerRegistryService

   Register an event listener to be notified when events of a given type are received via the Server JMS Event Queue.

   :param listener: the listener instance
   :param subjects: the event types that a listener is interested in

registerListener
^^^^^^^^^^^^^^^^

.. java:method::  void registerListener(EventListener listener, String subject)
   :outertype: EventListenerRegistryService

