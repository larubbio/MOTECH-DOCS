.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.web.context ConfigurableWebApplicationContext

.. java:import:: org.springframework.web.servlet DispatcherServlet

.. java:import:: javax.servlet ServletException

OsgiDispatcherServlet
=====================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class OsgiDispatcherServlet extends DispatcherServlet

Constructors
------------
OsgiDispatcherServlet
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public OsgiDispatcherServlet(BundleContext bundleContext)
   :outertype: OsgiDispatcherServlet

OsgiDispatcherServlet
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public OsgiDispatcherServlet(BundleContext bundleContext, ConfigurableWebApplicationContext configurableWebApplicationContext)
   :outertype: OsgiDispatcherServlet

Methods
-------
initFrameworkServlet
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected void initFrameworkServlet() throws ServletException
   :outertype: OsgiDispatcherServlet

postProcessWebApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected void postProcessWebApplicationContext(ConfigurableWebApplicationContext wac)
   :outertype: OsgiDispatcherServlet

