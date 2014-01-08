.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp CouchDbInstance

.. java:import:: org.ektorp.impl StdCouchDbInstance

.. java:import:: org.ektorp.spring HttpClientFactoryBean

.. java:import:: org.motechproject.commons.api Tenant

.. java:import:: org.motechproject.commons.couchdb.service CouchDbManager

.. java:import:: org.motechproject.commons.couchdb.service DbConnectionException

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util Properties

CouchDbManagerImpl
==================

.. java:package:: org.motechproject.commons.couchdb.service.impl
   :noindex:

.. java:type:: public class CouchDbManagerImpl implements CouchDbManager

Constructors
------------
CouchDbManagerImpl
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public CouchDbManagerImpl(CoreConfigurationService coreConfigurationService, Properties couchdbProperties)
   :outertype: CouchDbManagerImpl

Methods
-------
getConnector
^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getConnector(String dbName)
   :outertype: CouchDbManagerImpl

