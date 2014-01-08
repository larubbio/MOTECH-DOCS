.. java:import:: org.apache.commons.collections MapUtils

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.config.domain ModulePropertiesRecord

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util ArrayList

.. java:import:: java.util LinkedList

.. java:import:: java.util List

.. java:import:: java.util Properties

AllModuleProperties
===================

.. java:package:: org.motechproject.config.repository
   :noindex:

.. java:type:: @Repository @View public class AllModuleProperties extends MotechBaseRepository<ModulePropertiesRecord>

   The \ ``AllModuleProperties``\  class is responsible for storing and retrieving module properties from the database. It allows to retrieve properties by module name and create/update records.

Constructors
------------
AllModuleProperties
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllModuleProperties(CouchDbConnector connector)
   :outertype: AllModuleProperties

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: public void addOrUpdate(ModulePropertiesRecord record)
   :outertype: AllModuleProperties

asProperties
^^^^^^^^^^^^

.. java:method:: public Properties asProperties(String module, String filename)
   :outertype: AllModuleProperties

byBundle
^^^^^^^^

.. java:method:: public List<ModulePropertiesRecord> byBundle(String bundle)
   :outertype: AllModuleProperties

byModuleAndFileName
^^^^^^^^^^^^^^^^^^^

.. java:method:: public ModulePropertiesRecord byModuleAndFileName(String module, String filename)
   :outertype: AllModuleProperties

byModuleName
^^^^^^^^^^^^

.. java:method:: public List<ModulePropertiesRecord> byModuleName(String module)
   :outertype: AllModuleProperties

retrieveFileNamesForModule
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> retrieveFileNamesForModule(String module)
   :outertype: AllModuleProperties

