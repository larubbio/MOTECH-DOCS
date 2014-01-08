.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: javax.annotation PostConstruct

UIServiceTracker
================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class UIServiceTracker extends ServiceTracker

Constructors
------------
UIServiceTracker
^^^^^^^^^^^^^^^^

.. java:constructor:: public UIServiceTracker(BundleContext context, ModuleRegistrationData moduleRegistrationData)
   :outertype: UIServiceTracker

UIServiceTracker
^^^^^^^^^^^^^^^^

.. java:constructor:: public UIServiceTracker(BundleContextWrapper wrapper, ModuleRegistrationData moduleRegistrationData)
   :outertype: UIServiceTracker

Methods
-------
addingService
^^^^^^^^^^^^^

.. java:method:: @Override public Object addingService(ServiceReference ref)
   :outertype: UIServiceTracker

removedService
^^^^^^^^^^^^^^

.. java:method:: @Override public void removedService(ServiceReference ref, Object service)
   :outertype: UIServiceTracker

start
^^^^^

.. java:method:: @PostConstruct public void start()
   :outertype: UIServiceTracker

