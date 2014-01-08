.. java:import:: junit.framework Assert

.. java:import:: org.apache.log4j Level

.. java:import:: org.apache.log4j LogManager

.. java:import:: org.apache.log4j Logger

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.motechproject.osgi.web.repository AllLogMappings

.. java:import:: org.motechproject.osgi.web.service.impl ServerLogServiceImpl

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: java.util List

ServerLogServiceTest
====================

.. java:package:: org.motechproject.osgi.web.service
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class ServerLogServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: ServerLogServiceTest

shouldChangeLogLevels
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldChangeLogLevels() throws Exception
   :outertype: ServerLogServiceTest

shouldChangeRootLogLevel
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldChangeRootLogLevel()
   :outertype: ServerLogServiceTest

shouldGetLogLevels
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetLogLevels()
   :outertype: ServerLogServiceTest

shouldGetRootLogLevel
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetRootLogLevel()
   :outertype: ServerLogServiceTest

shouldRemoveLogLevels
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRemoveLogLevels() throws Exception
   :outertype: ServerLogServiceTest

