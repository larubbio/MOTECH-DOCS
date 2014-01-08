.. java:import:: java.util List

CouchLoggableEvent
==================

.. java:package:: org.motechproject.eventlogging.domain
   :noindex:

.. java:type:: public class CouchLoggableEvent extends LoggableEvent

Constructors
------------
CouchLoggableEvent
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CouchLoggableEvent(List<String> eventSubjects, List<? extends EventFlag> flags, CouchLogMappings mappings)
   :outertype: CouchLoggableEvent

Methods
-------
getMappings
^^^^^^^^^^^

.. java:method:: public CouchLogMappings getMappings()
   :outertype: CouchLoggableEvent

setMappings
^^^^^^^^^^^

.. java:method:: public void setMappings(CouchLogMappings mappings)
   :outertype: CouchLoggableEvent

