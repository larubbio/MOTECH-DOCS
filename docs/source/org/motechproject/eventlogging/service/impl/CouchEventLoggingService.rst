.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.converter.impl DefaultCouchToLogConverter

.. java:import:: org.motechproject.eventlogging.domain CouchLogMappings

.. java:import:: org.motechproject.eventlogging.domain CouchLoggableEvent

.. java:import:: org.motechproject.eventlogging.domain KeyValue

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.motechproject.eventlogging.domain MappingsJson

.. java:import:: org.motechproject.eventlogging.domain ParametersPresentEventFlag

.. java:import:: org.motechproject.eventlogging.loggers.impl CouchEventLogger

.. java:import:: org.motechproject.eventlogging.repository AllCouchLogs

.. java:import:: org.motechproject.eventlogging.repository AllEventMappings

.. java:import:: org.motechproject.eventlogging.service EventLoggingService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: javax.annotation PostConstruct

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

CouchEventLoggingService
========================

.. java:package:: org.motechproject.eventlogging.service.impl
   :noindex:

.. java:type:: @Service public class CouchEventLoggingService implements EventLoggingService

Constructors
------------
CouchEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CouchEventLoggingService()
   :outertype: CouchEventLoggingService

CouchEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CouchEventLoggingService(AllEventMappings allEventMappings)
   :outertype: CouchEventLoggingService

CouchEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CouchEventLoggingService(List<CouchEventLogger> couchEventLoggers)
   :outertype: CouchEventLoggingService

Methods
-------
getAllCouchLogs
^^^^^^^^^^^^^^^

.. java:method:: public AllCouchLogs getAllCouchLogs()
   :outertype: CouchEventLoggingService

getAllEventMappings
^^^^^^^^^^^^^^^^^^^

.. java:method:: public AllEventMappings getAllEventMappings()
   :outertype: CouchEventLoggingService

getCouchEventLoggers
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<CouchEventLogger> getCouchEventLoggers()
   :outertype: CouchEventLoggingService

getDefaultCouchEventLogger
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public CouchEventLogger getDefaultCouchEventLogger()
   :outertype: CouchEventLoggingService

getDefaultCouchToLogConverter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public DefaultCouchToLogConverter getDefaultCouchToLogConverter()
   :outertype: CouchEventLoggingService

getLoggedEventSubjects
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Set<String> getLoggedEventSubjects()
   :outertype: CouchEventLoggingService

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(MotechEvent event)
   :outertype: CouchEventLoggingService

setAllCouchLogs
^^^^^^^^^^^^^^^

.. java:method:: public void setAllCouchLogs(AllCouchLogs allCouchLogs)
   :outertype: CouchEventLoggingService

setAllEventMappings
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setAllEventMappings(AllEventMappings allEventMappings)
   :outertype: CouchEventLoggingService

setCouchEventLoggers
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setCouchEventLoggers(List<CouchEventLogger> couchEventLoggers)
   :outertype: CouchEventLoggingService

setDefaultCouchEventLogger
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setDefaultCouchEventLogger(CouchEventLogger defaultCouchEventLogger)
   :outertype: CouchEventLoggingService

setDefaultCouchToLogConverter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setDefaultCouchToLogConverter(DefaultCouchToLogConverter defaultCouchToLogConverter)
   :outertype: CouchEventLoggingService

