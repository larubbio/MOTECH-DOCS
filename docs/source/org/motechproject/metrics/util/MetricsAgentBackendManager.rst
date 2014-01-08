.. java:import:: org.eclipse.gemini.blueprint.service.importer OsgiServiceLifecycleListener

.. java:import:: org.motechproject.metrics MetricsAgentBackend

.. java:import:: org.motechproject.metrics.domain ConfigProperty

.. java:import:: org.motechproject.metrics.impl MultipleMetricsAgentImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

MetricsAgentBackendManager
==========================

.. java:package:: org.motechproject.metrics.util
   :noindex:

.. java:type:: @Component public class MetricsAgentBackendManager implements OsgiServiceLifecycleListener

   Class for managing metrics agent backend implementations available as services Allows getting available and used implementations as well as setting new ones as used

Constructors
------------
MetricsAgentBackendManager
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MetricsAgentBackendManager()
   :outertype: MetricsAgentBackendManager

Methods
-------
bind
^^^^

.. java:method:: @Override public void bind(Object service, Map serviceProperties)
   :outertype: MetricsAgentBackendManager

getAvailableMetricsAgentImplementations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Map<String, MetricsAgentBackend> getAvailableMetricsAgentImplementations()
   :outertype: MetricsAgentBackendManager

getSettings
^^^^^^^^^^^

.. java:method:: public Map<String, ConfigProperty> getSettings(String implName)
   :outertype: MetricsAgentBackendManager

getUsedMetricsAgents
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getUsedMetricsAgents()
   :outertype: MetricsAgentBackendManager

saveSettings
^^^^^^^^^^^^

.. java:method:: public void saveSettings(String implName, Map<String, ConfigProperty> config)
   :outertype: MetricsAgentBackendManager

setMetricsAgents
^^^^^^^^^^^^^^^^

.. java:method:: public void setMetricsAgents(List<String> selected)
   :outertype: MetricsAgentBackendManager

unbind
^^^^^^

.. java:method:: @Override public void unbind(Object service, Map serviceProperties)
   :outertype: MetricsAgentBackendManager

