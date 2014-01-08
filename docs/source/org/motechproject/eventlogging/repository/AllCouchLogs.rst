.. java:import:: org.ektorp ComplexKey

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.eventlogging.domain CouchEventLog

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllCouchLogs
============

.. java:package:: org.motechproject.eventlogging.repository
   :noindex:

.. java:type:: @Repository public class AllCouchLogs extends MotechBaseRepository<CouchEventLog>

Constructors
------------
AllCouchLogs
^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllCouchLogs(CouchDbConnector db)
   :outertype: AllCouchLogs

Methods
-------
findAllByParameter
^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<CouchEventLog> findAllByParameter(String parameter, String value)
   :outertype: AllCouchLogs

findAllBySubject
^^^^^^^^^^^^^^^^

.. java:method:: @View public List<CouchEventLog> findAllBySubject(String subject)
   :outertype: AllCouchLogs

findAllBySubjectAndParameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<CouchEventLog> findAllBySubjectAndParameter(String subject, String parameter, String value)
   :outertype: AllCouchLogs

log
^^^

.. java:method:: public void log(CouchEventLog couchLog)
   :outertype: AllCouchLogs

