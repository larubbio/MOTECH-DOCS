.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util Collections

.. java:import:: java.util List

LoggableEvent
=============

.. java:package:: org.motechproject.eventlogging.domain
   :noindex:

.. java:type:: public class LoggableEvent

Constructors
------------
LoggableEvent
^^^^^^^^^^^^^

.. java:constructor:: public LoggableEvent(List<String> eventSubjects, List<? extends EventFlag> flags)
   :outertype: LoggableEvent

Methods
-------
getEventSubjects
^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getEventSubjects()
   :outertype: LoggableEvent

getFlags
^^^^^^^^

.. java:method:: public List<? extends EventFlag> getFlags()
   :outertype: LoggableEvent

isLoggableEvent
^^^^^^^^^^^^^^^

.. java:method:: public boolean isLoggableEvent(MotechEvent eventToLog)
   :outertype: LoggableEvent

setEventSubjects
^^^^^^^^^^^^^^^^

.. java:method:: public void setEventSubjects(List<String> eventSubjects)
   :outertype: LoggableEvent

setFlags
^^^^^^^^

.. java:method:: public void setFlags(List<? extends EventFlag> flags)
   :outertype: LoggableEvent

