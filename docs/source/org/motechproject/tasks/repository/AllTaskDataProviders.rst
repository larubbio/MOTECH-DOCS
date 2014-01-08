.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllTaskDataProviders
====================

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @Repository @View public class AllTaskDataProviders extends MotechBaseRepository<TaskDataProvider>

Constructors
------------
AllTaskDataProviders
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllTaskDataProviders(CouchDbConnector connector)
   :outertype: AllTaskDataProviders

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: public boolean addOrUpdate(TaskDataProvider entity)
   :outertype: AllTaskDataProviders

byName
^^^^^^

.. java:method:: public TaskDataProvider byName(String name)
   :outertype: AllTaskDataProviders

