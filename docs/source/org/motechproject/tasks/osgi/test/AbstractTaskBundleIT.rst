.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain EventParameter

.. java:import:: org.motechproject.tasks.domain TaskEvent

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io IOException

.. java:import:: java.util List

.. java:import:: java.util SortedSet

AbstractTaskBundleIT
====================

.. java:package:: org.motechproject.tasks.osgi.test
   :noindex:

.. java:type:: public class AbstractTaskBundleIT extends BaseOsgiIT

Methods
-------
findActionEventBySubject
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected ActionEvent findActionEventBySubject(List<ActionEvent> actionEvents, String subject)
   :outertype: AbstractTaskBundleIT

findChannel
^^^^^^^^^^^

.. java:method:: protected Channel findChannel(String channelName) throws IOException
   :outertype: AbstractTaskBundleIT

findTaskEventBySubject
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected TaskEvent findTaskEventBySubject(List<? extends TaskEvent> taskEvents, String subject)
   :outertype: AbstractTaskBundleIT

findTriggerEventBySubject
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected TriggerEvent findTriggerEventBySubject(List<TriggerEvent> triggerEvents, String subject)
   :outertype: AbstractTaskBundleIT

hasActionParameterKey
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected boolean hasActionParameterKey(String externalIdKey, SortedSet<ActionParameter> actionParameters)
   :outertype: AbstractTaskBundleIT

hasEventParameterKey
^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected boolean hasEventParameterKey(String externalIdKey, List<EventParameter> eventParameters)
   :outertype: AbstractTaskBundleIT

