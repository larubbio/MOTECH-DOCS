.. java:import:: org.eclipse.gemini.blueprint.service.importer OsgiServiceLifecycleListener

.. java:import:: org.motechproject.event.metrics MetricsAgent

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util Map

MetricsServiceManager
=====================

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: @Component public class MetricsServiceManager implements OsgiServiceLifecycleListener

   The \ ``MetricsServiceManager``\  class is used for calling Metrics Agent's functions. It is done using metric's OSGi service which is obtained during runtime.

Methods
-------
bind
^^^^

.. java:method:: @Override public void bind(Object service, Map serviceProperties)
   :outertype: MetricsServiceManager

getService
^^^^^^^^^^

.. java:method:: public MetricsAgent getService()
   :outertype: MetricsServiceManager

isServiceAvailable
^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isServiceAvailable()
   :outertype: MetricsServiceManager

unbind
^^^^^^

.. java:method:: @Override public void unbind(Object service, Map serviceProperties)
   :outertype: MetricsServiceManager

