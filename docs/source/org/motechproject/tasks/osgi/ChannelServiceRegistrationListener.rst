.. java:import:: org.eclipse.gemini.blueprint.service.exporter OsgiServiceRegistrationListener

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: java.util Map

ChannelServiceRegistrationListener
==================================

.. java:package:: org.motechproject.tasks.osgi
   :noindex:

.. java:type:: public class ChannelServiceRegistrationListener implements OsgiServiceRegistrationListener

   A listener for \ :java:ref:`ChannelService`\ , effectively serves as a tasks-bundle start handler, that sets up tracking of start/stop events of all other bundles

Constructors
------------
ChannelServiceRegistrationListener
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ChannelServiceRegistrationListener(BundleContext bundleContext)
   :outertype: ChannelServiceRegistrationListener

Methods
-------
registered
^^^^^^^^^^

.. java:method:: @Override public void registered(Object service, Map serviceProperties)
   :outertype: ChannelServiceRegistrationListener

unregistered
^^^^^^^^^^^^

.. java:method:: @Override public void unregistered(Object service, Map serviceProperties)
   :outertype: ChannelServiceRegistrationListener

