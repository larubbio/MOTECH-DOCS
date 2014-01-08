.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllSettings
===========

.. java:package:: org.motechproject.server.config.repository
   :noindex:

.. java:type:: @Repository public class AllSettings extends MotechBaseRepository<SettingsRecord>

Constructors
------------
AllSettings
^^^^^^^^^^^

.. java:constructor:: @Autowired public AllSettings(CouchDbConnector couchDbConnector)
   :outertype: AllSettings

Methods
-------
addOrUpdateSettings
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void addOrUpdateSettings(SettingsRecord settingsRecord)
   :outertype: AllSettings

getSettings
^^^^^^^^^^^

.. java:method:: public SettingsRecord getSettings()
   :outertype: AllSettings

