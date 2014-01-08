.. java:import:: org.motechproject.commons.api DataProvider

.. java:import:: org.motechproject.tasks.domain DataSource

.. java:import:: org.motechproject.tasks.domain FilterSet

.. java:import:: org.motechproject.tasks.domain TaskConfigStep

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.util HashMap

.. java:import:: java.util Iterator

.. java:import:: java.util Map

TaskInitializer
===============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type::  class TaskInitializer

   The \ ``TaskInitializer``\  class prepares an action in the task definition to execution.

   ..

   * \ **evalConfigSteps**\  - executes all config steps (load data sources, check filters) defined in the task,

Constructors
------------
TaskInitializer
^^^^^^^^^^^^^^^

.. java:constructor::  TaskInitializer(TaskContext taskContext)
   :outertype: TaskInitializer

Methods
-------
evalConfigSteps
^^^^^^^^^^^^^^^

.. java:method:: public boolean evalConfigSteps(Map<String, DataProvider> dataProviders) throws TaskHandlerException
   :outertype: TaskInitializer

