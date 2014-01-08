.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.tasks.domain TaskActivity

.. java:import:: org.motechproject.tasks.service TaskActivityService

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ActivityControllerTest
======================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: public class ActivityControllerTest

Fields
------
activityService
^^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskActivityService activityService
   :outertype: ActivityControllerTest

controller
^^^^^^^^^^

.. java:field::  ActivityController controller
   :outertype: ActivityControllerTest

expected
^^^^^^^^

.. java:field::  List<TaskActivity> expected
   :outertype: ActivityControllerTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: ActivityControllerTest

shouldGetAllActivities
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllActivities()
   :outertype: ActivityControllerTest

shouldGetTaskActivities
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetTaskActivities()
   :outertype: ActivityControllerTest

shouldRemoveAllActivitiesForTask
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveAllActivitiesForTask()
   :outertype: ActivityControllerTest

