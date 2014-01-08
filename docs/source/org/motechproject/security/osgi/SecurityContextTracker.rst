.. java:import:: org.motechproject.commons.api ApplicationContextServiceReferenceUtils

.. java:import:: org.motechproject.security.annotations SecurityAnnotationBeanPostProcessor

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.motechproject.security.service SecurityRoleLoader

.. java:import:: org.motechproject.security.service SecurityRuleLoader

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.util.tracker ServiceTracker

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: java.util ArrayList

.. java:import:: java.util List

SecurityContextTracker
======================

.. java:package:: org.motechproject.security.osgi
   :noindex:

.. java:type:: public class SecurityContextTracker extends ServiceTracker

   A \ :java:ref:`ServiceTracker`\  that tracks \ :java:ref:`ApplicationContext`\  objects published as OSGi services. When a new context becomes available it processed by this class using \ :java:ref:`SecurityAnnotationBeanPostProcessor`\  for processing permissions declared by the module in its annotations. It also uses a \ :java:ref:`SecurityRoleLoader`\  for loading \ ``role.json``\  files contained in the module.

Constructors
------------
SecurityContextTracker
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SecurityContextTracker(BundleContext bundleContext, MotechRoleService roleService, MotechPermissionService permissionService, SecurityRuleLoader securityRuleLoader)
   :outertype: SecurityContextTracker

Methods
-------
addingService
^^^^^^^^^^^^^

.. java:method:: @Override public Object addingService(ServiceReference reference)
   :outertype: SecurityContextTracker

