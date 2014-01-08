.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.domain TaskActivityType

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.motechproject.tasks.repository AllTaskActivities

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: java.util ArrayList

.. java:import:: java.util List

TaskActivityServiceImplTest
===========================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: public class TaskActivityServiceImplTest

Fields
------
activityService
^^^^^^^^^^^^^^^

.. java:field::  TaskActivityService activityService
   :outertype: TaskActivityServiceImplTest

allTaskActivities
^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  AllTaskActivities allTaskActivities
   :outertype: TaskActivityServiceImplTest

task
^^^^

.. java:field::  Task task
   :outertype: TaskActivityServiceImplTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: TaskActivityServiceImplTest

shouldAddErrorActivityWithMessage
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddErrorActivityWithMessage()
   :outertype: TaskActivityServiceImplTest

shouldAddErrorActivityWithTaskException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddErrorActivityWithTaskException()
   :outertype: TaskActivityServiceImplTest

shouldAddTaskSuccessActivity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddTaskSuccessActivity()
   :outertype: TaskActivityServiceImplTest

shouldAddTaskWarningActivity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddTaskWarningActivity()
   :outertype: TaskActivityServiceImplTest

shouldAddTaskWarningActivityWithGivenException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddTaskWarningActivityWithGivenException()
   :outertype: TaskActivityServiceImplTest

shouldAddTaskWarningActivityWithGivenKeyAndField
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddTaskWarningActivityWithGivenKeyAndField()
   :outertype: TaskActivityServiceImplTest

shouldDeleteAllTaskActivitiesForGivenTask
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldDeleteAllTaskActivitiesForGivenTask()
   :outertype: TaskActivityServiceImplTest

shouldNotRemoveAnyActivitiesWhenTaskHasNotActivities
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRemoveAnyActivitiesWhenTaskHasNotActivities()
   :outertype: TaskActivityServiceImplTest

shouldReturnAllActivities
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllActivities()
   :outertype: TaskActivityServiceImplTest

shouldReturnAllActivitiesForGivenTask
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnAllActivitiesForGivenTask()
   :outertype: TaskActivityServiceImplTest

shouldReturnEmptyListWhenTaskHasNotActivities
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnEmptyListWhenTaskHasNotActivities()
   :outertype: TaskActivityServiceImplTest

shouldReturnTaskActivitiesForTaskFromLastErrorActivity
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnTaskActivitiesForTaskFromLastErrorActivity()
   :outertype: TaskActivityServiceImplTest

