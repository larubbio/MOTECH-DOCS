.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllTaskActivities
=================

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @Repository @View public class AllTaskActivities extends MotechBaseRepository<TaskActivity>

Constructors
------------
AllTaskActivities
^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllTaskActivities(CouchDbConnector db)
   :outertype: AllTaskActivities

Methods
-------
byTaskId
^^^^^^^^

.. java:method:: public List<TaskActivity> byTaskId(String taskId)
   :outertype: AllTaskActivities

