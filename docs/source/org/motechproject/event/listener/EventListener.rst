.. java:import:: org.motechproject.event MotechEvent

EventListener
=============

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: public interface EventListener

Methods
-------
getIdentifier
^^^^^^^^^^^^^

.. java:method::  String getIdentifier()
   :outertype: EventListener

   Retrieve a unique identifier/key for the given listener class. This identifier is used when messages are destine for this specific listener type

   :return: Unique listener identifier/key

handle
^^^^^^

.. java:method::  void handle(MotechEvent event)
   :outertype: EventListener

   Handle an particular event that has been received

   :param event:

