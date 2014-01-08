.. java:import:: com.github.ldriscoll.ektorplucene CouchDbRepositorySupportWithLucene

.. java:import:: com.github.ldriscoll.ektorplucene CustomLuceneResult

.. java:import:: com.github.ldriscoll.ektorplucene LuceneAwareCouchDbConnector

.. java:import:: com.github.ldriscoll.ektorplucene LuceneQuery

.. java:import:: com.github.ldriscoll.ektorplucene.designdocument.annotation FullText

.. java:import:: com.github.ldriscoll.ektorplucene.designdocument.annotation Index

.. java:import:: org.codehaus.jackson.type TypeReference

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.impl StdCouchDbInstance

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.lucene.query CouchDbLuceneQuery

.. java:import:: org.motechproject.commons.couchdb.query QueryParam

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.email.service EmailRecordSearchCriteria

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: org.springframework.util CollectionUtils

.. java:import:: java.io IOException

.. java:import:: java.lang.reflect Field

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllEmailRecords
===============

.. java:package:: org.motechproject.email.repository
   :noindex:

.. java:type:: @Repository public final class AllEmailRecords extends CouchDbRepositorySupportWithLucene<EmailRecord>

   The \ ``AllEmailRecords``\  class provides methods, allowing to work with, alter and search {@Link EmailRecord} documents in CouchDB

Methods
-------
findAllBy
^^^^^^^^^

.. java:method:: @FullText public List<EmailRecord> findAllBy(EmailRecordSearchCriteria criteria)
   :outertype: AllEmailRecords

findLatestBy
^^^^^^^^^^^^

.. java:method:: public EmailRecord findLatestBy(String toAddress)
   :outertype: AllEmailRecords

removeAll
^^^^^^^^^

.. java:method:: public void removeAll()
   :outertype: AllEmailRecords

