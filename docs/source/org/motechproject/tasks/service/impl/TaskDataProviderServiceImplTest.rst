.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.tasks.domain FieldParameter

.. java:import:: org.motechproject.tasks.domain LookupFieldsParameter

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.domain TaskDataProviderObject

.. java:import:: org.motechproject.tasks.ex ValidationException

.. java:import:: org.motechproject.tasks.repository AllTaskDataProviders

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: java.io ByteArrayInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.lang.reflect Type

.. java:import:: java.util ArrayList

.. java:import:: java.util List

TaskDataProviderServiceImplTest
===============================

.. java:package:: org.motechproject.tasks.service.impl
   :noindex:

.. java:type:: public class TaskDataProviderServiceImplTest

Fields
------
allTaskDataProviders
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  AllTaskDataProviders allTaskDataProviders
   :outertype: TaskDataProviderServiceImplTest

eventRelay
^^^^^^^^^^

.. java:field:: @Mock  EventRelay eventRelay
   :outertype: TaskDataProviderServiceImplTest

inputStream
^^^^^^^^^^^

.. java:field:: @Mock  InputStream inputStream
   :outertype: TaskDataProviderServiceImplTest

motechJsonReader
^^^^^^^^^^^^^^^^

.. java:field:: @Mock  MotechJsonReader motechJsonReader
   :outertype: TaskDataProviderServiceImplTest

taskDataProviderService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  TaskDataProviderService taskDataProviderService
   :outertype: TaskDataProviderServiceImplTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: TaskDataProviderServiceImplTest

shouldGetAllProviders
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetAllProviders()
   :outertype: TaskDataProviderServiceImplTest

shouldGetProviderById
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetProviderById()
   :outertype: TaskDataProviderServiceImplTest

shouldGetProviderByName
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetProviderByName()
   :outertype: TaskDataProviderServiceImplTest

shouldNotSaveProviderWhenValidationExceptionIsAppeared
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotSaveProviderWhenValidationExceptionIsAppeared()
   :outertype: TaskDataProviderServiceImplTest

shouldRegisterProviderFromInputStream
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterProviderFromInputStream()
   :outertype: TaskDataProviderServiceImplTest

shouldRegisterProviderFromString
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterProviderFromString() throws IOException
   :outertype: TaskDataProviderServiceImplTest

shouldSendEventWhenProviderWasUpdated
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSendEventWhenProviderWasUpdated()
   :outertype: TaskDataProviderServiceImplTest

