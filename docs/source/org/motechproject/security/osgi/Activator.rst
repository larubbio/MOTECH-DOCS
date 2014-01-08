.. java:import:: org.apache.felix.http.api ExtHttpService

.. java:import:: org.motechproject.osgi.web Header

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web MotechOsgiWebApplicationContext

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.osgi.web.exception ServletRegistrationException

.. java:import:: org.motechproject.osgi.web.ext HttpContextFactory

.. java:import:: org.motechproject.security.constants PermissionNames

.. java:import:: org.motechproject.security.filter MotechDelegatingFilterProxy

.. java:import:: org.motechproject.security.service MotechProxyManager

.. java:import:: org.osgi.framework BundleActivator

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.service.http HttpContext

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.web.filter DelegatingFilterProxy

.. java:import:: org.springframework.web.servlet DispatcherServlet

Activator
=========

.. java:package:: org.motechproject.security.osgi
   :noindex:

.. java:type:: public class Activator implements BundleActivator

   The Spring security activator is used to register the spring security filter, dispatcher servlet, and MotechProxyManager, which is necessary for supporting dynamic security. When initializing the security chain, the DB will be consulted for security configuration, if it's not there then the default security filter from the securityContext file is used.

Methods
-------
setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: public static void setBundleContext(BundleContext context)
   :outertype: Activator

start
^^^^^

.. java:method:: @Override public void start(BundleContext context)
   :outertype: Activator

stop
^^^^

.. java:method:: public void stop(BundleContext context)
   :outertype: Activator

