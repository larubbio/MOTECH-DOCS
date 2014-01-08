.. java:import:: org.eclipse.gemini.blueprint.service.importer OsgiServiceLifecycleListener

.. java:import:: org.motechproject.commons.api DataProvider

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.motechproject.tasks.service TaskTriggerHandler

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io IOException

.. java:import:: java.util Map

ManagementDataProvider
======================

.. java:package:: org.motechproject.tasks.util
   :noindex:

.. java:type:: @Component public class ManagementDataProvider implements OsgiServiceLifecycleListener

Constructors
------------
ManagementDataProvider
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ManagementDataProvider(TaskDataProviderService taskDataProviderService)
   :outertype: ManagementDataProvider

ManagementDataProvider
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ManagementDataProvider(TaskTriggerHandler handler, TaskDataProviderService taskDataProviderService)
   :outertype: ManagementDataProvider

Methods
-------
bind
^^^^

.. java:method:: @Override public void bind(Object service, Map serviceProperties) throws IOException
   :outertype: ManagementDataProvider

unbind
^^^^^^

.. java:method:: @Override public void unbind(Object service, Map serviceProperties)
   :outertype: ManagementDataProvider

