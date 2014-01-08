.. java:import:: org.apache.commons.vfs FileChangeEvent

.. java:import:: org.apache.commons.vfs FileListener

.. java:import:: org.apache.commons.vfs FileObject

.. java:import:: org.apache.commons.vfs FileSystemException

.. java:import:: org.apache.commons.vfs VFS

.. java:import:: org.apache.commons.vfs.impl DefaultFileMonitor

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.filters ConfigFileFilter

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: javax.annotation PostConstruct

.. java:import:: javax.annotation PreDestroy

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.lang.reflect InvocationTargetException

.. java:import:: java.lang.reflect Method

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

ConfigFileMonitor
=================

.. java:package:: org.motechproject.config.monitor
   :noindex:

.. java:type:: public class ConfigFileMonitor implements FileListener

   The \ ``ConfigFileMonitor``\  is used to monitor changes in config files and send appropriate events.

Constructors
------------
ConfigFileMonitor
^^^^^^^^^^^^^^^^^

.. java:constructor::  ConfigFileMonitor()
   :outertype: ConfigFileMonitor

ConfigFileMonitor
^^^^^^^^^^^^^^^^^

.. java:constructor:: public ConfigFileMonitor(ConfigLoader configLoader, ConfigurationService configurationService, CoreConfigurationService coreConfigurationService) throws FileSystemException
   :outertype: ConfigFileMonitor

Methods
-------
fileChanged
^^^^^^^^^^^

.. java:method:: @Override public void fileChanged(FileChangeEvent fileChangeEvent)
   :outertype: ConfigFileMonitor

fileCreated
^^^^^^^^^^^

.. java:method:: @Override public void fileCreated(FileChangeEvent fileChangeEvent) throws IOException
   :outertype: ConfigFileMonitor

fileDeleted
^^^^^^^^^^^

.. java:method:: @Override public void fileDeleted(FileChangeEvent fileChangeEvent) throws FileSystemException
   :outertype: ConfigFileMonitor

init
^^^^

.. java:method:: @PostConstruct public void init() throws IOException
   :outertype: ConfigFileMonitor

stop
^^^^

.. java:method:: @PreDestroy public void stop() throws FileSystemException
   :outertype: ConfigFileMonitor

updateFileMonitor
^^^^^^^^^^^^^^^^^

.. java:method:: public void updateFileMonitor() throws FileSystemException
   :outertype: ConfigFileMonitor

