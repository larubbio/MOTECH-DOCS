.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.converter EventToLogConverter

.. java:import:: org.motechproject.eventlogging.domain CouchEventLog

.. java:import:: org.motechproject.eventlogging.domain CouchLogMappings

.. java:import:: org.motechproject.eventlogging.domain CouchLoggableEvent

.. java:import:: org.motechproject.eventlogging.domain KeyValue

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

DefaultCouchToLogConverter
==========================

.. java:package:: org.motechproject.eventlogging.converter.impl
   :noindex:

.. java:type:: @Component public class DefaultCouchToLogConverter implements EventToLogConverter<CouchEventLog>

Methods
-------
configuredConvertEventToCouchLog
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public CouchEventLog configuredConvertEventToCouchLog(MotechEvent eventToLog, LoggableEvent loggableEvent)
   :outertype: DefaultCouchToLogConverter

convertToLog
^^^^^^^^^^^^

.. java:method:: @Override public CouchEventLog convertToLog(MotechEvent eventToLog)
   :outertype: DefaultCouchToLogConverter

