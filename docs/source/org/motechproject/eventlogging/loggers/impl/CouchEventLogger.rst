.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.converter.impl DefaultCouchToLogConverter

.. java:import:: org.motechproject.eventlogging.domain CouchEventLog

.. java:import:: org.motechproject.eventlogging.domain CouchLoggableEvent

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.motechproject.eventlogging.loggers EventLogger

.. java:import:: org.motechproject.eventlogging.repository AllCouchLogs

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

CouchEventLogger
================

.. java:package:: org.motechproject.eventlogging.loggers.impl
   :noindex:

.. java:type:: @Component public class CouchEventLogger extends EventLogger

Constructors
------------
CouchEventLogger
^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public CouchEventLogger(AllCouchLogs allCouchLogs, DefaultCouchToLogConverter eventConverter)
   :outertype: CouchEventLogger

Methods
-------
log
^^^

.. java:method:: @Override public void log(MotechEvent eventToLog)
   :outertype: CouchEventLogger

