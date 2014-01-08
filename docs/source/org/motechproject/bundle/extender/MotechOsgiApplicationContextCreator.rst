.. java:import:: org.apache.commons.logging Log

.. java:import:: org.apache.commons.logging LogFactory

.. java:import:: org.eclipse.gemini.blueprint.context DelegatedExecutionOsgiBundleApplicationContext

.. java:import:: org.eclipse.gemini.blueprint.extender OsgiApplicationContextCreator

.. java:import:: org.eclipse.gemini.blueprint.extender.support ApplicationContextConfiguration

.. java:import:: org.eclipse.gemini.blueprint.extender.support.scanning ConfigurationScanner

.. java:import:: org.eclipse.gemini.blueprint.extender.support.scanning DefaultConfigurationScanner

.. java:import:: org.eclipse.gemini.blueprint.util OsgiStringUtils

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.util Assert

.. java:import:: org.springframework.util ObjectUtils

MotechOsgiApplicationContextCreator
===================================

.. java:package:: org.motechproject.bundle.extender
   :noindex:

.. java:type:: public class MotechOsgiApplicationContextCreator implements OsgiApplicationContextCreator

Methods
-------
createApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public DelegatedExecutionOsgiBundleApplicationContext createApplicationContext(BundleContext bundleContext)
   :outertype: MotechOsgiApplicationContextCreator

setConfigurationScanner
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setConfigurationScanner(ConfigurationScanner configurationScanner)
   :outertype: MotechOsgiApplicationContextCreator

