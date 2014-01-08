.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

DefaultBundleFilter
===================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: @Component public class DefaultBundleFilter extends MotechBundleFilter

   The default implementation of the \ :java:ref:`MotechBundleFilter`\ . It gives a pass only for non-platform \ :java:ref:`Bundle`\ s that import or export the \ ``org.motechproject``\  package. To be counted as non-platform, the symbolic name of the \ :java:ref:`Bundle`\  mustn't start with \ ``"org.motechproject.motech-platform"``\ . Because the system bundle(\ ``org.apache.felix.framework``\ ) also imports/exports the \ ``org.motechproject``\  package, it is treated as an exception that will not pass the filter.

Methods
-------
passesCriteria
^^^^^^^^^^^^^^

.. java:method:: @Override public boolean passesCriteria(Bundle bundle)
   :outertype: DefaultBundleFilter

