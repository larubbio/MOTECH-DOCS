.. java:import:: org.eclipse.gemini.blueprint.context.support OsgiBundleXmlApplicationContext

.. java:import:: org.springframework.web.context ConfigurableWebApplicationContext

.. java:import:: javax.servlet ServletConfig

.. java:import:: javax.servlet ServletContext

MotechOsgiWebApplicationContext
===============================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class MotechOsgiWebApplicationContext extends OsgiBundleXmlApplicationContext implements ConfigurableWebApplicationContext

Constructors
------------
MotechOsgiWebApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechOsgiWebApplicationContext()
   :outertype: MotechOsgiWebApplicationContext

Methods
-------
getNamespace
^^^^^^^^^^^^

.. java:method:: @Override public String getNamespace()
   :outertype: MotechOsgiWebApplicationContext

getServletConfig
^^^^^^^^^^^^^^^^

.. java:method:: @Override public ServletConfig getServletConfig()
   :outertype: MotechOsgiWebApplicationContext

getServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ServletContext getServletContext()
   :outertype: MotechOsgiWebApplicationContext

setConfigLocation
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setConfigLocation(String configLocation)
   :outertype: MotechOsgiWebApplicationContext

setNamespace
^^^^^^^^^^^^

.. java:method:: @Override public void setNamespace(String namespace)
   :outertype: MotechOsgiWebApplicationContext

setServletConfig
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setServletConfig(ServletConfig servletConfig)
   :outertype: MotechOsgiWebApplicationContext

setServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setServletContext(ServletContext servletContext)
   :outertype: MotechOsgiWebApplicationContext

