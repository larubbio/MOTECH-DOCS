.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskBuilder

.. java:import:: org.motechproject.tasks.domain TaskEventInformation

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

AllTasksIT
==========

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllTasksIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: AllTasksIT

shouldAddAndUpdateTask
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddAndUpdateTask()
   :outertype: AllTasksIT

shouldAddTaskAsNewIfItHasIDAndTaskNotExistInDB
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddTaskAsNewIfItHasIDAndTaskNotExistInDB()
   :outertype: AllTasksIT

shouldFindTasksByTriggerSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindTasksByTriggerSubject()
   :outertype: AllTasksIT

shouldFindTasksThatDependOnAModule
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldFindTasksThatDependOnAModule()
   :outertype: AllTasksIT

