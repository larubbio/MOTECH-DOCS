.. java:import:: org.eclipse.gemini.blueprint.util OsgiStringUtils

.. java:import:: org.motechproject.osgi.web.exception ServletRegistrationException

.. java:import:: org.motechproject.osgi.web.ext HttpContextFactory

.. java:import:: org.motechproject.osgi.web.util WebBundleUtil

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.service.http HttpContext

.. java:import:: org.osgi.service.http HttpService

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.web.context ConfigurableWebApplicationContext

.. java:import:: org.springframework.web.servlet DispatcherServlet

.. java:import:: java.util Map

HttpServiceTracker
==================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class HttpServiceTracker extends ServiceTracker

Constructors
------------
HttpServiceTracker
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public HttpServiceTracker(BundleContext context, Map<String, String> resourceMapping)
   :outertype: HttpServiceTracker

Methods
-------
addingService
^^^^^^^^^^^^^

.. java:method:: @Override public Object addingService(ServiceReference serviceReference)
   :outertype: HttpServiceTracker

removedService
^^^^^^^^^^^^^^

.. java:method:: @Override public void removedService(ServiceReference ref, Object service)
   :outertype: HttpServiceTracker

start
^^^^^

.. java:method:: public void start()
   :outertype: HttpServiceTracker

unregister
^^^^^^^^^^

.. java:method:: public void unregister()
   :outertype: HttpServiceTracker

