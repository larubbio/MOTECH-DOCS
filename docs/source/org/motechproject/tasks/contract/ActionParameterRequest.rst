.. java:import:: java.util Objects

ActionParameterRequest
======================

.. java:package:: org.motechproject.tasks.contract
   :noindex:

.. java:type:: public class ActionParameterRequest implements Comparable<ActionParameterRequest>

   Object representation of a parameter in the channel action request definition.

Constructors
------------
ActionParameterRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameterRequest(String key, String displayName, Integer order, String type, boolean required)
   :outertype: ActionParameterRequest

ActionParameterRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameterRequest(String key, String displayName, Integer order, String type)
   :outertype: ActionParameterRequest

ActionParameterRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameterRequest(String key, String displayName, Integer order)
   :outertype: ActionParameterRequest

ActionParameterRequest
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionParameterRequest(String key, String displayName)
   :outertype: ActionParameterRequest

Methods
-------
compareTo
^^^^^^^^^

.. java:method:: @Override public int compareTo(ActionParameterRequest o)
   :outertype: ActionParameterRequest

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ActionParameterRequest

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: ActionParameterRequest

getKey
^^^^^^

.. java:method:: public String getKey()
   :outertype: ActionParameterRequest

getOrder
^^^^^^^^

.. java:method:: public Integer getOrder()
   :outertype: ActionParameterRequest

getType
^^^^^^^

.. java:method:: public String getType()
   :outertype: ActionParameterRequest

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ActionParameterRequest

isRequired
^^^^^^^^^^

.. java:method:: public boolean isRequired()
   :outertype: ActionParameterRequest

setOrder
^^^^^^^^

.. java:method:: public void setOrder(int order)
   :outertype: ActionParameterRequest

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ActionParameterRequest

