.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: java.io InputStream

.. java:import:: java.util List

TaskDataProviderService
=======================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public interface TaskDataProviderService

Methods
-------
getProvider
^^^^^^^^^^^

.. java:method::  TaskDataProvider getProvider(String name)
   :outertype: TaskDataProviderService

getProviderById
^^^^^^^^^^^^^^^

.. java:method::  TaskDataProvider getProviderById(String providerId)
   :outertype: TaskDataProviderService

getProviders
^^^^^^^^^^^^

.. java:method::  List<TaskDataProvider> getProviders()
   :outertype: TaskDataProviderService

registerProvider
^^^^^^^^^^^^^^^^

.. java:method::  TaskDataProvider registerProvider(String json)
   :outertype: TaskDataProviderService

registerProvider
^^^^^^^^^^^^^^^^

.. java:method::  TaskDataProvider registerProvider(InputStream stream)
   :outertype: TaskDataProviderService

