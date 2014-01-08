.. java:import:: org.codehaus.jackson.annotate JsonSubTypes

.. java:import:: org.codehaus.jackson.annotate JsonTypeInfo

.. java:import:: java.io Serializable

.. java:import:: java.util Objects

TaskConfigStep
==============

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @JsonTypeInfo @JsonSubTypes public abstract class TaskConfigStep implements Comparable<TaskConfigStep>, Serializable

Methods
-------
compareTo
^^^^^^^^^

.. java:method:: @Override public int compareTo(TaskConfigStep o)
   :outertype: TaskConfigStep

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskConfigStep

getOrder
^^^^^^^^

.. java:method:: public Integer getOrder()
   :outertype: TaskConfigStep

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskConfigStep

setOrder
^^^^^^^^

.. java:method:: public void setOrder(Integer order)
   :outertype: TaskConfigStep

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskConfigStep

