.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.admin.messages ActionType

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

NotificationRule
================

.. java:package:: org.motechproject.admin.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class NotificationRule extends MotechBaseDataObject

   A notification rule persisted in the database. Represents a rule for sending out a single notification. Contains information about this notification's recipient and the \ :java:ref:`ActionType`\  representing a method used for notifying the recipient.

Constructors
------------
NotificationRule
^^^^^^^^^^^^^^^^

.. java:constructor:: public NotificationRule()
   :outertype: NotificationRule

NotificationRule
^^^^^^^^^^^^^^^^

.. java:constructor:: public NotificationRule(String recipient, ActionType actionType)
   :outertype: NotificationRule

Methods
-------
getActionType
^^^^^^^^^^^^^

.. java:method:: public ActionType getActionType()
   :outertype: NotificationRule

getRecipient
^^^^^^^^^^^^

.. java:method:: public String getRecipient()
   :outertype: NotificationRule

setActionType
^^^^^^^^^^^^^

.. java:method:: public void setActionType(ActionType actionType)
   :outertype: NotificationRule

setRecipient
^^^^^^^^^^^^

.. java:method:: public void setRecipient(String recipient)
   :outertype: NotificationRule

