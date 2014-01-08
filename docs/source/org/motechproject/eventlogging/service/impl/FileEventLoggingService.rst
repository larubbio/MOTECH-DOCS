.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.motechproject.eventlogging.loggers EventLogger

.. java:import:: org.motechproject.eventlogging.loggers.impl FileEventLogger

.. java:import:: org.motechproject.eventlogging.service EventLoggingService

.. java:import:: java.util ArrayList

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Set

FileEventLoggingService
=======================

.. java:package:: org.motechproject.eventlogging.service.impl
   :noindex:

.. java:type:: public class FileEventLoggingService implements EventLoggingService

Constructors
------------
FileEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public FileEventLoggingService()
   :outertype: FileEventLoggingService

FileEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public FileEventLoggingService(List<FileEventLogger> fileEventLoggers)
   :outertype: FileEventLoggingService

Methods
-------
getLoggedEventSubjects
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Set<String> getLoggedEventSubjects()
   :outertype: FileEventLoggingService

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(MotechEvent event)
   :outertype: FileEventLoggingService

