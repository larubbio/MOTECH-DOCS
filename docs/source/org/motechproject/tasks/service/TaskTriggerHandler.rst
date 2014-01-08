.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.collections MapUtils

.. java:import:: org.apache.commons.lang.exception ExceptionUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api DataProvider

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.event.listener.annotations MotechListenerEventProxy

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TriggerEvent

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Service

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.reflect Method

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

TaskTriggerHandler
==================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: @Service public class TaskTriggerHandler implements TriggerHandler

   The \ ``TaskTriggerHandler``\  receives events and executes tasks for which the trigger event subject is the same as the received event subject.

Constructors
------------
TaskTriggerHandler
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskTriggerHandler(TaskService taskService, TaskActivityService activityService, EventListenerRegistryService registryService, EventRelay eventRelay, SettingsFacade settings)
   :outertype: TaskTriggerHandler

Methods
-------
addDataProvider
^^^^^^^^^^^^^^^

.. java:method:: public void addDataProvider(String taskDataProviderId, DataProvider provider)
   :outertype: TaskTriggerHandler

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event) throws TriggerNotFoundException
   :outertype: TaskTriggerHandler

registerHandlerFor
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public final void registerHandlerFor(String subject)
   :outertype: TaskTriggerHandler

removeDataProvider
^^^^^^^^^^^^^^^^^^

.. java:method:: public void removeDataProvider(String taskDataProviderId)
   :outertype: TaskTriggerHandler

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: @Autowired public void setBundleContext(BundleContext bundleContext)
   :outertype: TaskTriggerHandler

setDataProviders
^^^^^^^^^^^^^^^^

.. java:method::  void setDataProviders(Map<String, DataProvider> dataProviders)
   :outertype: TaskTriggerHandler

