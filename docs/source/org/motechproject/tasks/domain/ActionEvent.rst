.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ActionParameterRequest

.. java:import:: java.util Objects

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

ActionEvent
===========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class ActionEvent extends TaskEvent

Constructors
------------
ActionEvent
^^^^^^^^^^^

.. java:constructor:: public ActionEvent()
   :outertype: ActionEvent

ActionEvent
^^^^^^^^^^^

.. java:constructor:: public ActionEvent(String displayName, String subject, String description, SortedSet<ActionParameter> actionParameters)
   :outertype: ActionEvent

ActionEvent
^^^^^^^^^^^

.. java:constructor:: public ActionEvent(String displayName, String description, String serviceInterface, String serviceMethod, SortedSet<ActionParameter> actionParameters)
   :outertype: ActionEvent

ActionEvent
^^^^^^^^^^^

.. java:constructor:: public ActionEvent(String displayName, String subject, String description, String serviceInterface, String serviceMethod, SortedSet<ActionParameter> actionParameters)
   :outertype: ActionEvent

ActionEvent
^^^^^^^^^^^

.. java:constructor:: public ActionEvent(ActionEventRequest actionEventRequest)
   :outertype: ActionEvent

Methods
-------
accept
^^^^^^

.. java:method:: @JsonIgnore public boolean accept(TaskActionInformation info)
   :outertype: ActionEvent

addParameter
^^^^^^^^^^^^

.. java:method:: public void addParameter(ActionParameter parameter, boolean changeOrder)
   :outertype: ActionEvent

containsParameter
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean containsParameter(String key)
   :outertype: ActionEvent

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ActionEvent

getActionParameters
^^^^^^^^^^^^^^^^^^^

.. java:method:: public SortedSet<ActionParameter> getActionParameters()
   :outertype: ActionEvent

getServiceInterface
^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceInterface()
   :outertype: ActionEvent

getServiceMethod
^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceMethod()
   :outertype: ActionEvent

hasService
^^^^^^^^^^

.. java:method:: public boolean hasService()
   :outertype: ActionEvent

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ActionEvent

setActionParameters
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setActionParameters(SortedSet<ActionParameter> actionParameters)
   :outertype: ActionEvent

setServiceInterface
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setServiceInterface(String serviceInterface)
   :outertype: ActionEvent

setServiceMethod
^^^^^^^^^^^^^^^^

.. java:method:: public void setServiceMethod(String serviceMethod)
   :outertype: ActionEvent

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ActionEvent

