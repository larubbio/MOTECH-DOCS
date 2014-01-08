.. java:import:: org.eclipse.gemini.blueprint.context.support OsgiBundleXmlApplicationContext

.. java:import:: org.springframework.web.context ConfigurableWebApplicationContext

.. java:import:: javax.servlet ServletConfig

.. java:import:: javax.servlet ServletContext

MotechOsgiConfigurableApplicationContext
========================================

.. java:package:: org.motechproject.bundle.extender
   :noindex:

.. java:type:: public class MotechOsgiConfigurableApplicationContext extends OsgiBundleXmlApplicationContext implements ConfigurableWebApplicationContext

Constructors
------------
MotechOsgiConfigurableApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechOsgiConfigurableApplicationContext(String configurationLocations)
   :outertype: MotechOsgiConfigurableApplicationContext

Methods
-------
getNamespace
^^^^^^^^^^^^

.. java:method:: @Override public String getNamespace()
   :outertype: MotechOsgiConfigurableApplicationContext

getServletConfig
^^^^^^^^^^^^^^^^

.. java:method:: @Override public ServletConfig getServletConfig()
   :outertype: MotechOsgiConfigurableApplicationContext

getServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ServletContext getServletContext()
   :outertype: MotechOsgiConfigurableApplicationContext

setConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setConfigLocation(String configLocation)
   :outertype: MotechOsgiConfigurableApplicationContext

setNamespace
^^^^^^^^^^^^

.. java:method:: @Override public void setNamespace(String namespace)
   :outertype: MotechOsgiConfigurableApplicationContext

setServletConfig
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setServletConfig(ServletConfig servletConfig)
   :outertype: MotechOsgiConfigurableApplicationContext

setServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setServletContext(ServletContext servletContext)
   :outertype: MotechOsgiConfigurableApplicationContext

