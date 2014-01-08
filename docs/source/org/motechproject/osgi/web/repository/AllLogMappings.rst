.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllLogMappings
==============

.. java:package:: org.motechproject.osgi.web.repository
   :noindex:

.. java:type:: @Repository public class AllLogMappings extends MotechBaseRepository<LogMapping>

   The \ ``AllLogMappings``\  class is used for getting information about loggers from database.

Constructors
------------
AllLogMappings
^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllLogMappings(CouchDbConnector connector)
   :outertype: AllLogMappings

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: public void addOrUpdate(LogMapping mapping)
   :outertype: AllLogMappings

byLogName
^^^^^^^^^

.. java:method:: @View public LogMapping byLogName(String logName)
   :outertype: AllLogMappings

removeByLogName
^^^^^^^^^^^^^^^

.. java:method:: public void removeByLogName(String name)
   :outertype: AllLogMappings

