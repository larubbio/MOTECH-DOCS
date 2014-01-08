.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.util ArrayList

.. java:import:: java.util HashSet

.. java:import:: java.util Iterator

.. java:import:: java.util List

.. java:import:: java.util Set

EventListenerTree
=================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: public class EventListenerTree

Constructors
------------
EventListenerTree
^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventListenerTree()
   :outertype: EventListenerTree

EventListenerTree
^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventListenerTree(String pathElement, EventListenerTree parent)
   :outertype: EventListenerTree

Methods
-------
addListener
^^^^^^^^^^^

.. java:method:: public void addListener(EventListener listener, String subject)
   :outertype: EventListenerTree

   Given a full path create the tree structure to store it

   :param listener:
   :param subject:

getListenerCount
^^^^^^^^^^^^^^^^

.. java:method:: public int getListenerCount(String subject)
   :outertype: EventListenerTree

getListeners
^^^^^^^^^^^^

.. java:method:: public Set<EventListener> getListeners(String subject)
   :outertype: EventListenerTree

   Given a subject path return all listeners registered for it

   :param subject:

getPathElement
^^^^^^^^^^^^^^

.. java:method:: public String getPathElement()
   :outertype: EventListenerTree

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: EventListenerTree

   Walk up the tree from this point building out the subject

hasListener
^^^^^^^^^^^

.. java:method:: public boolean hasListener(String subject)
   :outertype: EventListenerTree

removeAllListeners
^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeAllListeners(String beanName)
   :outertype: EventListenerTree

