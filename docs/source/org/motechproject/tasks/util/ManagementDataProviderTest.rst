.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.commons.api DataProvider

.. java:import:: org.motechproject.tasks.domain TaskDataProvider

.. java:import:: org.motechproject.tasks.service TaskDataProviderService

.. java:import:: org.motechproject.tasks.service TaskTriggerHandler

.. java:import:: java.io IOException

ManagementDataProviderTest
==========================

.. java:package:: org.motechproject.tasks.util
   :noindex:

.. java:type:: public class ManagementDataProviderTest

Fields
------
dataProvider
^^^^^^^^^^^^

.. java:field:: @Mock  DataProvider dataProvider
   :outertype: ManagementDataProviderTest

taskDataProviderService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskDataProviderService taskDataProviderService
   :outertype: ManagementDataProviderTest

taskTriggerHandler
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  TaskTriggerHandler taskTriggerHandler
   :outertype: ManagementDataProviderTest

Methods
-------
setup
^^^^^

.. java:method:: @Before public void setup() throws Exception
   :outertype: ManagementDataProviderTest

shouldNotBindForObjectOtherThanDataProvider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotBindForObjectOtherThanDataProvider() throws IOException
   :outertype: ManagementDataProviderTest

shouldNotRemoveProviderFromHandler
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRemoveProviderFromHandler() throws IOException
   :outertype: ManagementDataProviderTest

shouldNotUnbindForObjectOtherThanDataProvider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotUnbindForObjectOtherThanDataProvider() throws IOException
   :outertype: ManagementDataProviderTest

shouldRegisterProvider
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterProvider() throws IOException
   :outertype: ManagementDataProviderTest

shouldRegisterProviderAndAddToHandler
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRegisterProviderAndAddToHandler() throws IOException
   :outertype: ManagementDataProviderTest

shouldRemoveProviderFromHandler
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveProviderFromHandler() throws IOException
   :outertype: ManagementDataProviderTest

