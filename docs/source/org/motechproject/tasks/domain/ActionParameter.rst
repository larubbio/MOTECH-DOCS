.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: java.util Objects

ActionParameter
===============

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class ActionParameter extends Parameter implements Comparable<ActionParameter>

   Object representation of a parameter in the channel action definition.

Constructors
------------
ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter()
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, boolean required)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, Integer order)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, ParameterType type)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, ParameterType type, boolean required)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, ParameterType type, Integer order)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(ActionParameterRequest actionParameterRequest)
   :outertype: ActionParameter

ActionParameter
^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameter(String displayName, String key, ParameterType type, Integer order, boolean required)
   :outertype: ActionParameter

Methods
-------
compareTo
^^^^^^^^^

.. java:method:: @Override public int compareTo(ActionParameter o)
   :outertype: ActionParameter

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ActionParameter

getKey
^^^^^^

.. java:method:: public String getKey()
   :outertype: ActionParameter

getOrder
^^^^^^^^

.. java:method:: public Integer getOrder()
   :outertype: ActionParameter

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ActionParameter

isRequired
^^^^^^^^^^

.. java:method:: public boolean isRequired()
   :outertype: ActionParameter

setKey
^^^^^^

.. java:method:: public void setKey(String key)
   :outertype: ActionParameter

setOrder
^^^^^^^^

.. java:method:: public void setOrder(Integer order)
   :outertype: ActionParameter

setRequired
^^^^^^^^^^^

.. java:method:: public void setRequired(boolean required)
   :outertype: ActionParameter

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ActionParameter

