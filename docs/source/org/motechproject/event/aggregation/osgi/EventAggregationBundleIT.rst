.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationState

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEvent

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.service EventAggregationService

.. java:import:: org.motechproject.event.aggregation.model.schedule PeriodicAggregationRequest

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain RepeatingSchedulableJob

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

EventAggregationBundleIT
========================

.. java:package:: org.motechproject.event.aggregation.osgi
   :noindex:

.. java:type:: public class EventAggregationBundleIT extends BaseOsgiIT

Methods
-------
getConfigLocations
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected String getConfigLocations()
   :outertype: EventAggregationBundleIT

getImports
^^^^^^^^^^

.. java:method:: @Override protected List<String> getImports()
   :outertype: EventAggregationBundleIT

testEventAggregationScervice
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testEventAggregationScervice() throws InterruptedException
   :outertype: EventAggregationBundleIT

