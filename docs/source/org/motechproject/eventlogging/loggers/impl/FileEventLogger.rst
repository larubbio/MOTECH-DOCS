.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.converter.impl DefaultFileToLogConverter

.. java:import:: org.motechproject.eventlogging.domain LoggableEvent

.. java:import:: org.motechproject.eventlogging.loggers EventLogger

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io BufferedWriter

.. java:import:: java.io File

.. java:import:: java.io FileWriter

.. java:import:: java.io IOException

.. java:import:: java.util Collections

.. java:import:: java.util List

FileEventLogger
===============

.. java:package:: org.motechproject.eventlogging.loggers.impl
   :noindex:

.. java:type:: public class FileEventLogger extends EventLogger

Constructors
------------
FileEventLogger
^^^^^^^^^^^^^^^

.. java:constructor:: public FileEventLogger(DefaultFileToLogConverter eventConverter)
   :outertype: FileEventLogger

FileEventLogger
^^^^^^^^^^^^^^^

.. java:constructor:: public FileEventLogger(List<LoggableEvent> loggableEvents, List<File> loggingFiles, DefaultFileToLogConverter eventConverter)
   :outertype: FileEventLogger

Methods
-------
log
^^^

.. java:method:: @Override public void log(MotechEvent eventToLog)
   :outertype: FileEventLogger

log
^^^

.. java:method:: protected void log(String informationToLog)
   :outertype: FileEventLogger

