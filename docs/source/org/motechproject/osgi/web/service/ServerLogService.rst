.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: java.util List

ServerLogService
================

.. java:package:: org.motechproject.osgi.web.service
   :noindex:

.. java:type:: public interface ServerLogService

   Interface for accessing Logger's configuration from the database

Fields
------
CURRENT_LOGGERS_NAME
^^^^^^^^^^^^^^^^^^^^

.. java:field::  String CURRENT_LOGGERS_NAME
   :outertype: ServerLogService

ROOT_LOGGER_NAME
^^^^^^^^^^^^^^^^

.. java:field::  String ROOT_LOGGER_NAME
   :outertype: ServerLogService

Methods
-------
changeLogLevel
^^^^^^^^^^^^^^

.. java:method::  void changeLogLevel(String name, String level)
   :outertype: ServerLogService

changeRootLogLevel
^^^^^^^^^^^^^^^^^^

.. java:method::  void changeRootLogLevel(String level)
   :outertype: ServerLogService

getLogLevels
^^^^^^^^^^^^

.. java:method::  List<LogMapping> getLogLevels()
   :outertype: ServerLogService

getRootLogLevel
^^^^^^^^^^^^^^^

.. java:method::  LogMapping getRootLogLevel()
   :outertype: ServerLogService

reconfigure
^^^^^^^^^^^

.. java:method::  void reconfigure()
   :outertype: ServerLogService

removeLogger
^^^^^^^^^^^^

.. java:method::  void removeLogger(String name)
   :outertype: ServerLogService

