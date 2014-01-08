.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.map.annotate JsonDeserialize

.. java:import:: org.motechproject.tasks.json TaskConfigDeserializer

.. java:import:: java.io Serializable

.. java:import:: java.util NoSuchElementException

.. java:import:: java.util Objects

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

TaskConfig
==========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @JsonDeserialize public class TaskConfig implements Serializable

Methods
-------
add
^^^

.. java:method:: public TaskConfig add(TaskConfigStep... configSteps)
   :outertype: TaskConfig

addAll
^^^^^^

.. java:method:: public TaskConfig addAll(SortedSet<TaskConfigStep> set)
   :outertype: TaskConfig

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskConfig

getDataSource
^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public DataSource getDataSource(String providerId, Long objectId, String objectType)
   :outertype: TaskConfig

getDataSources
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public SortedSet<DataSource> getDataSources()
   :outertype: TaskConfig

getDataSources
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public SortedSet<DataSource> getDataSources(String providerId)
   :outertype: TaskConfig

getFilters
^^^^^^^^^^

.. java:method:: @JsonIgnore public SortedSet<FilterSet> getFilters()
   :outertype: TaskConfig

getSteps
^^^^^^^^

.. java:method:: public SortedSet<TaskConfigStep> getSteps()
   :outertype: TaskConfig

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskConfig

removeAll
^^^^^^^^^

.. java:method:: public TaskConfig removeAll()
   :outertype: TaskConfig

removeDataSources
^^^^^^^^^^^^^^^^^

.. java:method:: public TaskConfig removeDataSources()
   :outertype: TaskConfig

removeFilterSets
^^^^^^^^^^^^^^^^

.. java:method:: public TaskConfig removeFilterSets()
   :outertype: TaskConfig

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskConfig

