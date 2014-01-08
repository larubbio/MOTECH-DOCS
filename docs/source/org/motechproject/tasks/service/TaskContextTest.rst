.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.hamcrest Description

.. java:import:: org.hamcrest TypeSafeMatcher

.. java:import:: org.junit Rule

.. java:import:: org.junit Test

.. java:import:: org.junit.rules ExpectedException

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.mockito.runners MockitoJUnitRunner

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.tasks.domain KeyInformation

.. java:import:: org.motechproject.tasks.domain Task

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.domain TaskBuilder

.. java:import:: org.motechproject.tasks.events.constants TaskFailureCause

.. java:import:: org.motechproject.tasks.ex TaskHandlerException

.. java:import:: java.util HashMap

.. java:import:: java.util Map

TaskContextTest
===============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: @RunWith public class TaskContextTest

Fields
------
expectedException
^^^^^^^^^^^^^^^^^

.. java:field:: @Rule public ExpectedException expectedException
   :outertype: TaskContextTest

Methods
-------
shouldNotThrowExceptionWhenDataSourceFieldValueEvaluationThrowsException_IfFailNotFoundIsFalse
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotThrowExceptionWhenDataSourceFieldValueEvaluationThrowsException_IfFailNotFoundIsFalse() throws Exception
   :outertype: TaskContextTest

shouldNotThrowExceptionWhenDataSourceIsNull_IfFailNotFoundIsFalse
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotThrowExceptionWhenDataSourceIsNull_IfFailNotFoundIsFalse() throws Exception
   :outertype: TaskContextTest

shouldThrowExceptionWhenAccessingUnconfiguredDataSource
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenAccessingUnconfiguredDataSource() throws Exception
   :outertype: TaskContextTest

shouldThrowExceptionWhenDataSourceFieldValueEvaluationThrowsException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenDataSourceFieldValueEvaluationThrowsException() throws Exception
   :outertype: TaskContextTest

shouldThrowExceptionWhenDataSourceIsNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenDataSourceIsNull() throws Exception
   :outertype: TaskContextTest

testGetDataSourceValue
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetDataSourceValue() throws Exception
   :outertype: TaskContextTest

testGetNullTriggerKey
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetNullTriggerKey() throws Exception
   :outertype: TaskContextTest

testGetTriggerKey
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetTriggerKey() throws Exception
   :outertype: TaskContextTest

testGetTriggerKeyShouldThrowException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetTriggerKeyShouldThrowException() throws Exception
   :outertype: TaskContextTest

