.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.motechproject.admin.domain NotificationRule

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

AllNotificationRules
====================

.. java:package:: org.motechproject.admin.repository
   :noindex:

.. java:type:: @Repository public class AllNotificationRules extends MotechBaseRepository<NotificationRule>

   CouchDb repository for \ :java:ref:`NotificationRule`\ s.

Constructors
------------
AllNotificationRules
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllNotificationRules(CouchDbConnector db)
   :outertype: AllNotificationRules

