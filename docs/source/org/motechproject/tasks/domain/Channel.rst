.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.tasks.contract ActionEventRequest

.. java:import:: org.motechproject.tasks.contract ChannelRequest

.. java:import:: org.motechproject.tasks.contract TriggerEventRequest

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Objects

Channel
=======

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class Channel extends MotechBaseDataObject

Constructors
------------
Channel
^^^^^^^

.. java:constructor:: public Channel()
   :outertype: Channel

Channel
^^^^^^^

.. java:constructor:: public Channel(String displayName, String moduleName, String moduleVersion)
   :outertype: Channel

Channel
^^^^^^^

.. java:constructor:: public Channel(String displayName, String moduleName, String moduleVersion, String description, List<TriggerEvent> triggerTaskEvents, List<ActionEvent> actionTaskEvents)
   :outertype: Channel

Channel
^^^^^^^

.. java:constructor:: public Channel(ChannelRequest channelRequest)
   :outertype: Channel

Methods
-------
addActionTaskEvent
^^^^^^^^^^^^^^^^^^

.. java:method:: public void addActionTaskEvent(ActionEvent actionEvent)
   :outertype: Channel

containsAction
^^^^^^^^^^^^^^

.. java:method:: public boolean containsAction(TaskActionInformation actionInformation)
   :outertype: Channel

containsTrigger
^^^^^^^^^^^^^^^

.. java:method:: public boolean containsTrigger(TaskEventInformation triggerInformation)
   :outertype: Channel

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Channel

getAction
^^^^^^^^^

.. java:method:: public ActionEvent getAction(TaskActionInformation actionInformation)
   :outertype: Channel

getActionTaskEvents
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<ActionEvent> getActionTaskEvents()
   :outertype: Channel

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: Channel

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: Channel

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: Channel

getModuleVersion
^^^^^^^^^^^^^^^^

.. java:method:: public String getModuleVersion()
   :outertype: Channel

getTrigger
^^^^^^^^^^

.. java:method:: public TriggerEvent getTrigger(TaskEventInformation triggerInformation)
   :outertype: Channel

getTriggerTaskEvents
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<TriggerEvent> getTriggerTaskEvents()
   :outertype: Channel

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Channel

setActionTaskEvents
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setActionTaskEvents(List<ActionEvent> actionTaskEvents)
   :outertype: Channel

setDescription
^^^^^^^^^^^^^^

.. java:method:: public void setDescription(String description)
   :outertype: Channel

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: Channel

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: Channel

setModuleVersion
^^^^^^^^^^^^^^^^

.. java:method:: public void setModuleVersion(String moduleVersion)
   :outertype: Channel

setTriggerTaskEvents
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setTriggerTaskEvents(List<TriggerEvent> triggerTaskEvents)
   :outertype: Channel

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: Channel

