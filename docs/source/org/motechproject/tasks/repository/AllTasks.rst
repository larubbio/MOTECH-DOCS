.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp DocumentNotFoundException

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp ViewResult

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util HashMap

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

AllTasks
========

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @Repository public class AllTasks extends MotechBaseRepository<Task>

   A repository class for storing a \ :java:ref:`Task`\  into a couchdb database

Constructors
------------
AllTasks
^^^^^^^^

.. java:constructor:: @Autowired public AllTasks(CouchDbConnector connector)
   :outertype: AllTasks

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: public void addOrUpdate(Task task)
   :outertype: AllTasks

byTriggerSubject
^^^^^^^^^^^^^^^^

.. java:method:: @View public List<Task> byTriggerSubject(String subject)
   :outertype: AllTasks

dependentOnModule
^^^^^^^^^^^^^^^^^

.. java:method:: @View public List<Task> dependentOnModule(String moduleName)
   :outertype: AllTasks

