.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.motechproject.metrics MetricsAgentBackend

.. java:import:: org.motechproject.metrics StatsdAgentBackend

.. java:import:: org.motechproject.metrics.domain ConfigProperty

.. java:import:: org.motechproject.metrics.domain PropertyType

.. java:import:: org.motechproject.metrics.exception ValidationException

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: javax.annotation PostConstruct

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io FileOutputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net DatagramPacket

.. java:import:: java.net DatagramSocket

.. java:import:: java.net InetAddress

.. java:import:: java.net SocketException

.. java:import:: java.net UnknownHostException

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

StatsdAgentBackendImpl
======================

.. java:package:: org.motechproject.metrics.impl
   :noindex:

.. java:type:: public class StatsdAgentBackendImpl implements MetricsAgentBackend, StatsdAgentBackend

   A very simple metric backend that logs all metrics over UDP. The intended receiver is a statsd server (http://codeascraft.etsy.com/2011/02/15/measure-anything-measure-everything/)

Constructors
------------
StatsdAgentBackendImpl
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public StatsdAgentBackendImpl()
   :outertype: StatsdAgentBackendImpl

Methods
-------
getGraphiteUrl
^^^^^^^^^^^^^^

.. java:method:: public String getGraphiteUrl()
   :outertype: StatsdAgentBackendImpl

getImplementationName
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public String getImplementationName()
   :outertype: StatsdAgentBackendImpl

getServerHost
^^^^^^^^^^^^^

.. java:method:: public String getServerHost()
   :outertype: StatsdAgentBackendImpl

getServerPort
^^^^^^^^^^^^^

.. java:method:: public int getServerPort()
   :outertype: StatsdAgentBackendImpl

getSettings
^^^^^^^^^^^

.. java:method:: @Override public Map<String, ConfigProperty> getSettings()
   :outertype: StatsdAgentBackendImpl

isGenerateHostBasedStats
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isGenerateHostBasedStats()
   :outertype: StatsdAgentBackendImpl

loadProperties
^^^^^^^^^^^^^^

.. java:method:: @PostConstruct public void loadProperties()
   :outertype: StatsdAgentBackendImpl

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric, Map<String, String> parameters)
   :outertype: StatsdAgentBackendImpl

   Reports an occurrence of metric, incrementing it's count. Ignores parameters

   :param metric: The metric being recorded
   :param parameters: Ignored. Silently dropped. Actually this implementation laughs a little at you

logEvent
^^^^^^^^

.. java:method:: @Override public void logEvent(String metric)
   :outertype: StatsdAgentBackendImpl

   Reports an occurrence of metric, incrementing it's count.

   :param metric: The metric being recorded

logTimedEvent
^^^^^^^^^^^^^

.. java:method:: @Override public void logTimedEvent(String metric, long time)
   :outertype: StatsdAgentBackendImpl

   Reports an occurrence of metric in milliseconds

   :param metric: The metric being recorded
   :param time: The execution time of this event in milliseconds

saveProperties
^^^^^^^^^^^^^^

.. java:method:: public void saveProperties()
   :outertype: StatsdAgentBackendImpl

saveSettings
^^^^^^^^^^^^

.. java:method:: @Override public void saveSettings(Map<String, ConfigProperty> config)
   :outertype: StatsdAgentBackendImpl

setGenerateHostBasedStats
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setGenerateHostBasedStats(boolean generateHostBasedStats)
   :outertype: StatsdAgentBackendImpl

setGraphiteUrl
^^^^^^^^^^^^^^

.. java:method:: public void setGraphiteUrl(String url)
   :outertype: StatsdAgentBackendImpl

setServerHost
^^^^^^^^^^^^^

.. java:method:: public void setServerHost(String serverHost)
   :outertype: StatsdAgentBackendImpl

setServerPort
^^^^^^^^^^^^^

.. java:method:: public void setServerPort(int port)
   :outertype: StatsdAgentBackendImpl

