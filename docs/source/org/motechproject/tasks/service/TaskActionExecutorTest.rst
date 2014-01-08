.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.mockito.runners MockitoJUnitRunner

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskBuilder

.. java:import:: org.motechproject.tasks.ex ActionNotFoundException

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: java.util HashMap

.. java:import:: java.util TreeSet

TaskActionExecutorTest
======================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: @RunWith public class TaskActionExecutorTest

Methods
-------
shouldAddActivityNotificationIfServiceIsNotAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddActivityNotificationIfServiceIsNotAvailable() throws TaskHandlerException, ActionNotFoundException
   :outertype: TaskActionExecutorTest

shouldInvokeServiceIfActionHasService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldInvokeServiceIfActionHasService() throws ActionNotFoundException, TaskHandlerException
   :outertype: TaskActionExecutorTest

shouldNotRaiseEventIfActionHasSubjectAndService_IfServiceIsAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRaiseEventIfActionHasSubjectAndService_IfServiceIsAvailable() throws ActionNotFoundException, TaskHandlerException
   :outertype: TaskActionExecutorTest

shouldRaiseEventIfActionHasSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRaiseEventIfActionHasSubject() throws ActionNotFoundException, TaskHandlerException
   :outertype: TaskActionExecutorTest

shouldRaiseEventWhenActionHasSubjectAndService_IfServiceIsNotAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRaiseEventWhenActionHasSubjectAndService_IfServiceIsNotAvailable() throws TaskHandlerException, ActionNotFoundException
   :outertype: TaskActionExecutorTest

shouldThrowExceptionIfActionHasNeitherEventNorService
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfActionHasNeitherEventNorService() throws TaskHandlerException, ActionNotFoundException
   :outertype: TaskActionExecutorTest

shouldThrowExceptionIfBundleContextIsNotAvailable
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionIfBundleContextIsNotAvailable() throws TaskHandlerException, ActionNotFoundException
   :outertype: TaskActionExecutorTest

