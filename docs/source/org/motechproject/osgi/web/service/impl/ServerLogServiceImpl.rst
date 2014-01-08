.. java:import:: org.apache.log4j Level

.. java:import:: org.apache.log4j LogManager

.. java:import:: org.apache.log4j Logger

.. java:import:: org.motechproject.commons.api CastUtils

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.motechproject.osgi.web.repository AllLogMappings

.. java:import:: org.motechproject.osgi.web.service ServerLogService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

ServerLogServiceImpl
====================

.. java:package:: org.motechproject.osgi.web.service.impl
   :noindex:

.. java:type:: @Service public final class ServerLogServiceImpl implements ServerLogService

   Implementation of the ServerLogService Interface.

Constructors
------------
ServerLogServiceImpl
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ServerLogServiceImpl(AllLogMappings allLogMappings)
   :outertype: ServerLogServiceImpl

Methods
-------
changeLogLevel
^^^^^^^^^^^^^^

.. java:method:: @Override public void changeLogLevel(String name, String level)
   :outertype: ServerLogServiceImpl

changeRootLogLevel
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void changeRootLogLevel(String level)
   :outertype: ServerLogServiceImpl

getLogLevels
^^^^^^^^^^^^

.. java:method:: @Override public List<LogMapping> getLogLevels()
   :outertype: ServerLogServiceImpl

getRootLogLevel
^^^^^^^^^^^^^^^

.. java:method:: @Override public LogMapping getRootLogLevel()
   :outertype: ServerLogServiceImpl

reconfigure
^^^^^^^^^^^

.. java:method:: @Override public void reconfigure()
   :outertype: ServerLogServiceImpl

removeLogger
^^^^^^^^^^^^

.. java:method:: @Override public void removeLogger(String name)
   :outertype: ServerLogServiceImpl

