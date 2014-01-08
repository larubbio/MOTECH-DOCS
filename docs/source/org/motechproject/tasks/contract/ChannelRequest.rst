.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Objects

ChannelRequest
==============

.. java:package:: org.motechproject.tasks.contract
   :noindex:

.. java:type:: public class ChannelRequest

   Service layer object denoting a \ :java:ref:`org.motechproject.tasks.domain.Channel`\ . Used by \ :java:ref:`ChannelService`\

Constructors
------------
ChannelRequest
^^^^^^^^^^^^^^

.. java:constructor:: public ChannelRequest(String displayName, String moduleName, String moduleVersion, String description, List<TriggerEventRequest> triggerTaskEvents, List<ActionEventRequest> actionTaskEvents)
   :outertype: ChannelRequest

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ChannelRequest

getActionTaskEvents
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<ActionEventRequest> getActionTaskEvents()
   :outertype: ChannelRequest

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: ChannelRequest

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: ChannelRequest

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: ChannelRequest

getModuleVersion
^^^^^^^^^^^^^^^^

.. java:method:: public String getModuleVersion()
   :outertype: ChannelRequest

getTriggerTaskEvents
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<TriggerEventRequest> getTriggerTaskEvents()
   :outertype: ChannelRequest

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ChannelRequest

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: ChannelRequest

setModuleVersion
^^^^^^^^^^^^^^^^

.. java:method:: public void setModuleVersion(String moduleVersion)
   :outertype: ChannelRequest

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ChannelRequest

