.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.apache.http HttpStatus

.. java:import:: org.apache.log4j LogManager

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.osgi.web.service ServerLogService

.. java:import:: org.motechproject.osgi.web.settings Loggers

.. java:import:: org.motechproject.admin.web.controller ServerLogController

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.http MediaType

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.io File

.. java:import:: java.net URISyntaxException

.. java:import:: java.net URL

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ServerLogControllerTest
=======================

.. java:package:: org.motechproject.admin.web
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class ServerLogControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws URISyntaxException
   :outertype: ServerLogControllerTest

testChangeLogLevelsNullMap
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testChangeLogLevelsNullMap()
   :outertype: ServerLogControllerTest

testGetLog
^^^^^^^^^^

.. java:method:: @Test public void testGetLog() throws Exception
   :outertype: ServerLogControllerTest

testGetLogLevels
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetLogLevels()
   :outertype: ServerLogControllerTest

testMissingLog
^^^^^^^^^^^^^^

.. java:method:: @Test public void testMissingLog() throws Exception
   :outertype: ServerLogControllerTest

testMissingRaw
^^^^^^^^^^^^^^

.. java:method:: @Test public void testMissingRaw() throws Exception
   :outertype: ServerLogControllerTest

testRaw
^^^^^^^

.. java:method:: @Test public void testRaw() throws Exception
   :outertype: ServerLogControllerTest

