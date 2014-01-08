.. java:import:: java.util ArrayList

.. java:import:: java.util List

TaskBuilder
===========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class TaskBuilder

Constructors
------------
TaskBuilder
^^^^^^^^^^^

.. java:constructor:: public TaskBuilder()
   :outertype: TaskBuilder

Methods
-------
addAction
^^^^^^^^^

.. java:method:: public TaskBuilder addAction(TaskActionInformation action)
   :outertype: TaskBuilder

addDataSource
^^^^^^^^^^^^^

.. java:method:: public TaskBuilder addDataSource(DataSource dataSource)
   :outertype: TaskBuilder

addFilterSet
^^^^^^^^^^^^

.. java:method:: public TaskBuilder addFilterSet(FilterSet filterSet)
   :outertype: TaskBuilder

build
^^^^^

.. java:method:: public Task build()
   :outertype: TaskBuilder

clear
^^^^^

.. java:method:: public TaskBuilder clear()
   :outertype: TaskBuilder

isEnabled
^^^^^^^^^

.. java:method:: public TaskBuilder isEnabled(boolean enabled)
   :outertype: TaskBuilder

withDescription
^^^^^^^^^^^^^^^

.. java:method:: public TaskBuilder withDescription(String description)
   :outertype: TaskBuilder

withId
^^^^^^

.. java:method:: public TaskBuilder withId(String id)
   :outertype: TaskBuilder

withName
^^^^^^^^

.. java:method:: public TaskBuilder withName(String name)
   :outertype: TaskBuilder

withTaskConfig
^^^^^^^^^^^^^^

.. java:method:: public TaskBuilder withTaskConfig(TaskConfig taskConfig)
   :outertype: TaskBuilder

withTrigger
^^^^^^^^^^^

.. java:method:: public TaskBuilder withTrigger(TaskEventInformation trigger)
   :outertype: TaskBuilder

