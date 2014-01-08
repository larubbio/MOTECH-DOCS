.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleEvent

.. java:import:: org.osgi.framework SynchronousBundleListener

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: java.util HashMap

.. java:import:: java.util Map

UIServiceTrackers
=================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class UIServiceTrackers

Methods
-------
addTrackerFor
^^^^^^^^^^^^^

.. java:method:: public UIServiceTracker addTrackerFor(Bundle bundle, ApplicationContext applicationContext)
   :outertype: UIServiceTrackers

removeTrackerFor
^^^^^^^^^^^^^^^^

.. java:method:: public UIServiceTracker removeTrackerFor(Bundle bundle)
   :outertype: UIServiceTrackers

