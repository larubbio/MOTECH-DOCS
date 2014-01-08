.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util Set

EventLoggingService
===================

.. java:package:: org.motechproject.eventlogging.service
   :noindex:

.. java:type:: public interface EventLoggingService

   Class that represents a logging service. A logging service can provide any sort of implementation, but must be able to log events and return a list of events they log.

Methods
-------
getLoggedEventSubjects
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  Set<String> getLoggedEventSubjects()
   :outertype: EventLoggingService

   Returns a set of event subjects this logger is listening on.

   :return: The list of event subjects.

logEvent
^^^^^^^^

.. java:method::  void logEvent(MotechEvent event)
   :outertype: EventLoggingService

   Logs an event. This could be by file, couch, feed, etc.

   :param event: The event to log.

