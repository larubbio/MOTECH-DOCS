.. java:import:: org.osgi.framework Bundle

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MotechBundleFilter
==================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: public abstract class MotechBundleFilter

   An abstract class representing a filter for \ :java:ref:`Bundle`\  instances. Used by the \ :java:ref:`org.motechproject.admin.service.ModuleAdminService`\  to determine which \ :java:ref:`Bundle`\ s should be returned by it's listing methods.

Methods
-------
filter
^^^^^^

.. java:method:: public List<Bundle> filter(Bundle bundles)
   :outertype: MotechBundleFilter

   Filters the given \ :java:ref:`Bundle`\  array and returns a \ :java:ref:`List`\  containing entries that pass criteria. Only entries for which the \ :java:ref:`passesCriteria(org.osgi.framework.Bundle)`\  method returns true will be part of the returned \ :java:ref:`List`\ .

   :param bundles: the array of \ :java:ref:`Bundle`\  objects to be filtered.
   :return: a \ :java:ref:`List`\  containing the \ :java:ref:`Bundle`\  objects that pass the filter criteria.

passesCriteria
^^^^^^^^^^^^^^

.. java:method:: public abstract boolean passesCriteria(Bundle bundle)
   :outertype: MotechBundleFilter

   A method which has to be implemented by child classes. Determines whether the \ :java:ref:`Bundle`\  passes the filter criteria and should pass filtering.

   :param bundle: the \ :java:ref:`Bundle`\  to be filtered.
   :return: true if the \ :java:ref:`Bundle`\  passes filter criteria, false otherwise.

