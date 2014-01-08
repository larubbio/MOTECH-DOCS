.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.admin.domain StatusMessage

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllStatusMessages
=================

.. java:package:: org.motechproject.admin.repository
   :noindex:

.. java:type:: @Repository public class AllStatusMessages extends MotechBaseRepository<StatusMessage>

   CouchDb repository for \ :java:ref:`StatusMessage`\ s.

Constructors
------------
AllStatusMessages
^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllStatusMessages(CouchDbConnector connector)
   :outertype: AllStatusMessages

Methods
-------
getActiveMessages
^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<StatusMessage> getActiveMessages()
   :outertype: AllStatusMessages

   Retrieves all active messages, meaning all messages with a timeout not in the past.

   :return: all active messages.

