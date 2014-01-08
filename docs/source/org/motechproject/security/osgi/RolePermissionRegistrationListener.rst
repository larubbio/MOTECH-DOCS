.. java:import:: org.eclipse.gemini.blueprint.service.exporter OsgiServiceRegistrationListener

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service SecurityRuleLoader

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: java.util Map

RolePermissionRegistrationListener
==================================

.. java:package:: org.motechproject.security.osgi
   :noindex:

.. java:type:: public class RolePermissionRegistrationListener implements OsgiServiceRegistrationListener

   This class is responsible for creating the SecurityContextTracker once the security bundle has been started and processed

Methods
-------
registered
^^^^^^^^^^

.. java:method:: @Override public void registered(Object service, Map serviceProperties)
   :outertype: RolePermissionRegistrationListener

unregistered
^^^^^^^^^^^^

.. java:method:: @Override public void unregistered(Object service, Map serviceProperties)
   :outertype: RolePermissionRegistrationListener

