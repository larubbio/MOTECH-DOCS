.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: java.util ArrayList

.. java:import:: java.util List

EventLogger
===========

.. java:package:: org.motechproject.eventlogging.loggers
   :noindex:

.. java:type:: public abstract class EventLogger

   Class that represents a generic event logger. All loggers have a list of loggable events that they should be able to provide logging functionality for.

Methods
-------
addLoggableEvents
^^^^^^^^^^^^^^^^^

.. java:method:: public void addLoggableEvents(List<LoggableEvent> loggableEvents)
   :outertype: EventLogger

clearLoggableEvents
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void clearLoggableEvents()
   :outertype: EventLogger

getLoggableEvents
^^^^^^^^^^^^^^^^^

.. java:method:: public List<LoggableEvent> getLoggableEvents()
   :outertype: EventLogger

log
^^^

.. java:method:: public abstract void log(MotechEvent eventToLog)
   :outertype: EventLogger

removeLoggableEvents
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeLoggableEvents(List<LoggableEvent> loggableEvents)
   :outertype: EventLogger

