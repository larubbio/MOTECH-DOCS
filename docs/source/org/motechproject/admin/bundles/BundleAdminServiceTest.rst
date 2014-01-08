.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.admin.ex BundleNotFoundException

.. java:import:: org.motechproject.admin.service ModuleAdminService

.. java:import:: org.motechproject.admin.service.impl ModuleAdminServiceImpl

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.osgi.framework Version

.. java:import:: org.springframework.web.multipart.commons CommonsMultipartResolver

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net URL

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util Dictionary

.. java:import:: java.util List

BundleAdminServiceTest
======================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: public class BundleAdminServiceTest

Fields
------
bundle
^^^^^^

.. java:field:: @Mock  Bundle bundle
   :outertype: BundleAdminServiceTest

bundleContext
^^^^^^^^^^^^^

.. java:field:: @Mock  BundleContext bundleContext
   :outertype: BundleAdminServiceTest

bundleDirectoryManager
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  BundleDirectoryManager bundleDirectoryManager
   :outertype: BundleAdminServiceTest

commonsMultipartResolver
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  CommonsMultipartResolver commonsMultipartResolver
   :outertype: BundleAdminServiceTest

exposedServiceReference
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ServiceReference exposedServiceReference
   :outertype: BundleAdminServiceTest

file
^^^^

.. java:field:: @Mock  File file
   :outertype: BundleAdminServiceTest

headers
^^^^^^^

.. java:field:: @Mock  Dictionary<Object, Object> headers
   :outertype: BundleAdminServiceTest

importExportResolver
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ImportExportResolver importExportResolver
   :outertype: BundleAdminServiceTest

moduleAdminService
^^^^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  ModuleAdminService moduleAdminService
   :outertype: BundleAdminServiceTest

motechBundleFilter
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  MotechBundleFilter motechBundleFilter
   :outertype: BundleAdminServiceTest

motechSettings
^^^^^^^^^^^^^^

.. java:field:: @Mock  MotechSettings motechSettings
   :outertype: BundleAdminServiceTest

serviceReference
^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ServiceReference serviceReference
   :outertype: BundleAdminServiceTest

settingsFacade
^^^^^^^^^^^^^^

.. java:field:: @Mock  SettingsFacade settingsFacade
   :outertype: BundleAdminServiceTest

uiFrameworkService
^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  UIFrameworkService uiFrameworkService
   :outertype: BundleAdminServiceTest

version
^^^^^^^

.. java:field:: @Mock  Version version
   :outertype: BundleAdminServiceTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: BundleAdminServiceTest

testBundleIcon
^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleIcon() throws IOException
   :outertype: BundleAdminServiceTest

testBundleInfoNotFound
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleInfoNotFound()
   :outertype: BundleAdminServiceTest

testBundleRestartNotFound
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleRestartNotFound() throws BundleException
   :outertype: BundleAdminServiceTest

testBundleStartNotFound
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleStartNotFound() throws BundleException
   :outertype: BundleAdminServiceTest

testBundleStopNotFound
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testBundleStopNotFound() throws BundleException
   :outertype: BundleAdminServiceTest

testDefaultBundleIcon
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testDefaultBundleIcon()
   :outertype: BundleAdminServiceTest

testGet3rdPartyBundle
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGet3rdPartyBundle()
   :outertype: BundleAdminServiceTest

testGetBundleDetails
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleDetails()
   :outertype: BundleAdminServiceTest

testGetBundleInfo
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundleInfo()
   :outertype: BundleAdminServiceTest

testGetBundles
^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetBundles()
   :outertype: BundleAdminServiceTest

testRestartBundle
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRestartBundle() throws BundleException
   :outertype: BundleAdminServiceTest

testSetUploadSize
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testSetUploadSize()
   :outertype: BundleAdminServiceTest

testStartBundle
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testStartBundle() throws BundleException
   :outertype: BundleAdminServiceTest

testStopBundle
^^^^^^^^^^^^^^

.. java:method:: @Test public void testStopBundle() throws BundleException
   :outertype: BundleAdminServiceTest

testUnInstallBundle
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testUnInstallBundle() throws BundleException, IOException
   :outertype: BundleAdminServiceTest

