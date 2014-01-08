.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.repository AllEmailRecords

.. java:import:: org.motechproject.email.service EmailAuditService

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

EmailAuditServiceImpl
=====================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: @Service public class EmailAuditServiceImpl implements EmailAuditService

   The \ ``EmailAuditServiceImpl``\  class provides API for everything connected with logging e-mails and searching through them

Constructors
------------
EmailAuditServiceImpl
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public EmailAuditServiceImpl(AllEmailRecords allEmailRecords, SettingsFacade settings)
   :outertype: EmailAuditServiceImpl

Methods
-------
delete
^^^^^^

.. java:method:: @Override public void delete(EmailRecord emailRecord)
   :outertype: EmailAuditServiceImpl

findAllEmailRecords
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<EmailRecord> findAllEmailRecords()
   :outertype: EmailAuditServiceImpl

findEmailRecords
^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<EmailRecord> findEmailRecords(EmailRecordSearchCriteria criteria)
   :outertype: EmailAuditServiceImpl

log
^^^

.. java:method:: @Override public void log(EmailRecord emailRecord)
   :outertype: EmailAuditServiceImpl

