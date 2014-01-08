.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.admin.messages Level

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

StatusMessage
=============

.. java:package:: org.motechproject.admin.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class StatusMessage extends MotechBaseDataObject

   Represents a message displayed in the 'messages' section of the Admin UI. Persisted in CouchDB. Apart from the message and its \ :java:ref:`Level`\ , contains also information about the module that sent the message. The timeout field represents the \ :java:ref:`DateTime`\  of the message expiration.

Constructors
------------
StatusMessage
^^^^^^^^^^^^^

.. java:constructor:: public StatusMessage()
   :outertype: StatusMessage

StatusMessage
^^^^^^^^^^^^^

.. java:constructor:: public StatusMessage(String text)
   :outertype: StatusMessage

StatusMessage
^^^^^^^^^^^^^

.. java:constructor:: public StatusMessage(String text, String moduleName, Level level)
   :outertype: StatusMessage

StatusMessage
^^^^^^^^^^^^^

.. java:constructor:: public StatusMessage(String text, String moduleName, Level level, DateTime timeout)
   :outertype: StatusMessage

Methods
-------
getDate
^^^^^^^

.. java:method:: public DateTime getDate()
   :outertype: StatusMessage

getLevel
^^^^^^^^

.. java:method:: public Level getLevel()
   :outertype: StatusMessage

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: StatusMessage

getText
^^^^^^^

.. java:method:: public String getText()
   :outertype: StatusMessage

getTimeout
^^^^^^^^^^

.. java:method:: public DateTime getTimeout()
   :outertype: StatusMessage

setDate
^^^^^^^

.. java:method:: public void setDate(DateTime date)
   :outertype: StatusMessage

setLevel
^^^^^^^^

.. java:method:: public void setLevel(Level level)
   :outertype: StatusMessage

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: StatusMessage

setText
^^^^^^^

.. java:method:: public void setText(String text)
   :outertype: StatusMessage

setTimeout
^^^^^^^^^^

.. java:method:: public void setTimeout(DateTime timeout)
   :outertype: StatusMessage

setTimeoutAfter
^^^^^^^^^^^^^^^

.. java:method:: public void setTimeoutAfter(int minutes)
   :outertype: StatusMessage

