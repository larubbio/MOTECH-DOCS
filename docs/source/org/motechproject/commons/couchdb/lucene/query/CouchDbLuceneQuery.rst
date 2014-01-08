.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api Range

.. java:import:: java.util Set

CouchDbLuceneQuery
==================

.. java:package:: org.motechproject.commons.couchdb.lucene.query
   :noindex:

.. java:type:: public class CouchDbLuceneQuery

Fields
------
DATE_TIME_FORMAT
^^^^^^^^^^^^^^^^

.. java:field:: public static final String DATE_TIME_FORMAT
   :outertype: CouchDbLuceneQuery

Methods
-------
build
^^^^^

.. java:method:: public StringBuilder build()
   :outertype: CouchDbLuceneQuery

with
^^^^

.. java:method:: public CouchDbLuceneQuery with(String field, String value)
   :outertype: CouchDbLuceneQuery

withAny
^^^^^^^

.. java:method:: public CouchDbLuceneQuery withAny(String field, Set<String> values)
   :outertype: CouchDbLuceneQuery

withDate
^^^^^^^^

.. java:method:: public CouchDbLuceneQuery withDate(String field, DateTime value)
   :outertype: CouchDbLuceneQuery

withDateRange
^^^^^^^^^^^^^

.. java:method:: public CouchDbLuceneQuery withDateRange(String field, Range<DateTime> value)
   :outertype: CouchDbLuceneQuery

withField
^^^^^^^^^

.. java:method:: public CouchDbLuceneQuery withField(String field, String type, String value)
   :outertype: CouchDbLuceneQuery

withInt
^^^^^^^

.. java:method:: public CouchDbLuceneQuery withInt(String field, int value)
   :outertype: CouchDbLuceneQuery

