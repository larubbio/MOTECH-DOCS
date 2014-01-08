.. java:import:: org.apache.log4j Logger

.. java:import:: org.apache.log4j PropertyConfigurator

.. java:import:: org.apache.log4j.xml DOMConfigurator

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.motechproject.osgi.web.repository AllLogMappings

.. java:import:: org.motechproject.osgi.web.service ServerLogService

.. java:import:: org.motechproject.server.api BundleLoadingException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.w3c.dom Document

.. java:import:: org.w3c.dom Element

.. java:import:: org.w3c.dom Node

.. java:import:: org.w3c.dom NodeList

.. java:import:: org.xml.sax EntityResolver

.. java:import:: org.xml.sax InputSource

.. java:import:: org.xml.sax SAXException

.. java:import:: javax.annotation PostConstruct

.. java:import:: javax.xml.parsers DocumentBuilder

.. java:import:: javax.xml.parsers DocumentBuilderFactory

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringReader

.. java:import:: java.net URL

.. java:import:: java.net URLConnection

.. java:import:: java.util List

.. java:import:: java.util Properties

Log4JBundleLoader
=================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class Log4JBundleLoader

   This \ ``Log4JBundleLoader``\  class is responsible for loading logger's configuration from database or file(log4j.xml).

Methods
-------
checkListContainLogger
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean checkListContainLogger(List<LogMapping> loggers, String log)
   :outertype: Log4JBundleLoader

checkLogXmlConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean checkLogXmlConfiguration(Document log4jDoc)
   :outertype: Log4JBundleLoader

createLoggerProperties
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Properties createLoggerProperties(List<LogMapping> log)
   :outertype: Log4JBundleLoader

loadBundle
^^^^^^^^^^

.. java:method:: public void loadBundle(Bundle bundle) throws BundleLoadingException, IOException
   :outertype: Log4JBundleLoader

loadLoggerDbConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @PostConstruct public void loadLoggerDbConfiguration()
   :outertype: Log4JBundleLoader

setLog4jConf
^^^^^^^^^^^^

.. java:method:: public void setLog4jConf(String log4jConf)
   :outertype: Log4JBundleLoader

