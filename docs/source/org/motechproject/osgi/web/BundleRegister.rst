.. java:import:: org.osgi.framework Bundle

.. java:import:: java.util ArrayList

.. java:import:: java.util List

BundleRegister
==============

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public final class BundleRegister

   The \ ``BundleRegister``\  Singleton class is used for recording bundles. This class will help to reconfigure logger's levels.

Methods
-------
addBundle
^^^^^^^^^

.. java:method:: public void addBundle(Bundle bundle)
   :outertype: BundleRegister

getBundleList
^^^^^^^^^^^^^

.. java:method:: public List<Bundle> getBundleList()
   :outertype: BundleRegister

getInstance
^^^^^^^^^^^

.. java:method:: public static BundleRegister getInstance()
   :outertype: BundleRegister

