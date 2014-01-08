.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.ektorp DocumentNotFoundException

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.domain TaskError

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.repository AllTaskDataProviders

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.motechproject.tasks.validation TaskDataProviderValidator

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.io ByteArrayInputStream

.. java:import:: java.io InputStream

.. java:import:: java.lang.reflect Type

.. java:import:: java.nio.charset Charset

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

TaskDataProviderServiceImpl
===========================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: @Service public class TaskDataProviderServiceImpl implements TaskDataProviderService

Constructors
------------
TaskDataProviderServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public TaskDataProviderServiceImpl(AllTaskDataProviders allTaskDataProviders, EventRelay eventRelay)
   :outertype: TaskDataProviderServiceImpl

TaskDataProviderServiceImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskDataProviderServiceImpl(AllTaskDataProviders allTaskDataProviders, EventRelay eventRelay, MotechJsonReader motechJsonReader)
   :outertype: TaskDataProviderServiceImpl

Methods
-------
getProvider
^^^^^^^^^^^

.. java:method:: @Override public TaskDataProvider getProvider(String name)
   :outertype: TaskDataProviderServiceImpl

getProviderById
^^^^^^^^^^^^^^^

.. java:method:: @Override public TaskDataProvider getProviderById(String providerId)
   :outertype: TaskDataProviderServiceImpl

getProviders
^^^^^^^^^^^^

.. java:method:: @Override public List<TaskDataProvider> getProviders()
   :outertype: TaskDataProviderServiceImpl

registerProvider
^^^^^^^^^^^^^^^^

.. java:method:: @Override public TaskDataProvider registerProvider(String body)
   :outertype: TaskDataProviderServiceImpl

registerProvider
^^^^^^^^^^^^^^^^

.. java:method:: @Override public TaskDataProvider registerProvider(InputStream stream)
   :outertype: TaskDataProviderServiceImpl

