.. java:import:: org.apache.commons.lang.exception ExceptionUtils

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.service ModuleAdminService

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.admin.web.controller BundleAdminController

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: javax.servlet ServletOutputStream

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io PrintWriter

.. java:import:: java.util List

BundleAdminControllerTest
=========================

.. java:package:: org.motechproject.admin.web
   :noindex:

.. java:type:: public class BundleAdminControllerTest

Fields
------
bundleException
^^^^^^^^^^^^^^^

.. java:field:: @Mock  BundleException bundleException
   :outertype: BundleAdminControllerTest

bundleFile
^^^^^^^^^^

.. java:field:: @Mock  MultipartFile bundleFile
   :outertype: BundleAdminControllerTest

bundleIcon
^^^^^^^^^^

.. java:field:: @Mock  BundleIcon bundleIcon
   :outertype: BundleAdminControllerTest

bundleInformation
^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  BundleInformation bundleInformation
   :outertype: BundleAdminControllerTest

bundles
^^^^^^^

.. java:field:: @Mock  List<BundleInformation> bundles
   :outertype: BundleAdminControllerTest

controller
^^^^^^^^^^

.. java:field:: @InjectMocks  BundleAdminController controller
   :outertype: BundleAdminControllerTest

moduleAdminService
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ModuleAdminService moduleAdminService
   :outertype: BundleAdminControllerTest

outputStream
^^^^^^^^^^^^

.. java:field:: @Mock  ServletOutputStream outputStream
   :outertype: BundleAdminControllerTest

response
^^^^^^^^

.. java:field:: @Mock  HttpServletResponse response
   :outertype: BundleAdminControllerTest

statusMessageService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  StatusMessageService statusMessageService
   :outertype: BundleAdminControllerTest

writer
^^^^^^

.. java:field:: @Mock  PrintWriter writer
   :outertype: BundleAdminControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: BundleAdminControllerTest

testBundleException
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleException() throws IOException
   :outertype: BundleAdminControllerTest

testBundleList
^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleList()
   :outertype: BundleAdminControllerTest

testGetBundleIcon
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleIcon() throws IOException
   :outertype: BundleAdminControllerTest

testGetBundleInfo
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleInfo()
   :outertype: BundleAdminControllerTest

testRestartBundle
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRestartBundle() throws BundleException
   :outertype: BundleAdminControllerTest

testStartBundle
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testStartBundle() throws BundleException
   :outertype: BundleAdminControllerTest

testStopBundle
^^^^^^^^^^^^^^

.. java:method:: @Test public void testStopBundle() throws BundleException
   :outertype: BundleAdminControllerTest

testUninstallBundle
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testUninstallBundle() throws BundleException
   :outertype: BundleAdminControllerTest

testUploadBundle
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testUploadBundle() throws BundleException
   :outertype: BundleAdminControllerTest

