.. java:import:: java.util Objects

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

ActionEventRequest
==================

.. java:package:: org.motechproject.tasks.contract
   :noindex:

.. java:type:: public class ActionEventRequest

Constructors
------------
ActionEventRequest
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionEventRequest(String displayName, String subject, String description, String serviceInterface, String serviceMethod, SortedSet<ActionParameterRequest> actionParameters)
   :outertype: ActionEventRequest

ActionEventRequest
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ActionEventRequest(String displayName, String subject, String description, String serviceInterface, String serviceMethod)
   :outertype: ActionEventRequest

Methods
-------
addParameter
^^^^^^^^^^^^

.. java:method:: public void addParameter(ActionParameterRequest parameter, boolean changeOrder)
   :outertype: ActionEventRequest

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ActionEventRequest

getActionParameters
^^^^^^^^^^^^^^^^^^^

.. java:method:: public SortedSet<ActionParameterRequest> getActionParameters()
   :outertype: ActionEventRequest

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: ActionEventRequest

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: ActionEventRequest

getServiceInterface
^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceInterface()
   :outertype: ActionEventRequest

getServiceMethod
^^^^^^^^^^^^^^^^

.. java:method:: public String getServiceMethod()
   :outertype: ActionEventRequest

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: ActionEventRequest

hasService
^^^^^^^^^^

.. java:method:: public boolean hasService()
   :outertype: ActionEventRequest

hasSubject
^^^^^^^^^^

.. java:method:: public boolean hasSubject()
   :outertype: ActionEventRequest

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ActionEventRequest

isValid
^^^^^^^

.. java:method:: public boolean isValid()
   :outertype: ActionEventRequest

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ActionEventRequest

