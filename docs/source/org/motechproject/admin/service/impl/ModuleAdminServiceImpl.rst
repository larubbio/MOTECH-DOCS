.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.maven.wagon ConnectionException

.. java:import:: org.apache.maven.wagon Wagon

.. java:import:: org.apache.maven.wagon.authentication AuthenticationException

.. java:import:: org.apache.maven.wagon.providers.http LightweightHttpWagon

.. java:import:: org.motechproject.admin.bundles BundleDirectoryManager

.. java:import:: org.motechproject.admin.bundles ExtendedBundleInformation

.. java:import:: org.motechproject.admin.bundles ImportExportResolver

.. java:import:: org.motechproject.admin.bundles MotechBundleFilter

.. java:import:: org.motechproject.admin.ex BundleNotFoundException

.. java:import:: org.motechproject.admin.service ModuleAdminService

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.motechproject.server.api JarInformation

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.osgi.framework Constants

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.sonatype.aether RepositorySystem

.. java:import:: org.sonatype.aether.collection CollectRequest

.. java:import:: org.sonatype.aether.connector.wagon WagonProvider

.. java:import:: org.sonatype.aether.connector.wagon WagonRepositoryConnectorFactory

.. java:import:: org.sonatype.aether.graph Dependency

.. java:import:: org.sonatype.aether.repository LocalRepository

.. java:import:: org.sonatype.aether.repository RemoteRepository

.. java:import:: org.sonatype.aether.resolution ArtifactResult

.. java:import:: org.sonatype.aether.resolution DependencyRequest

.. java:import:: org.sonatype.aether.spi.connector RepositoryConnectorFactory

.. java:import:: org.sonatype.aether.util.artifact DefaultArtifact

.. java:import:: org.sonatype.aether.util.artifact JavaScopes

.. java:import:: org.sonatype.aether.util.filter DependencyFilterUtils

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: org.springframework.web.multipart.commons CommonsMultipartResolver

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net URL

.. java:import:: java.net URLConnection

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ModuleAdminServiceImpl
======================

.. java:package:: org.motechproject.admin.service.impl
   :noindex:

.. java:type:: @Service public class ModuleAdminServiceImpl implements ModuleAdminService

   Implementation of the \ :java:ref:`ModuleAdminService`\  interface for bundle management.

Methods
-------
changeMaxUploadSize
^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public void changeMaxUploadSize(MotechEvent event)
   :outertype: ModuleAdminServiceImpl

getBundleDetails
^^^^^^^^^^^^^^^^

.. java:method:: @Override public ExtendedBundleInformation getBundleDetails(long bundleId)
   :outertype: ModuleAdminServiceImpl

getBundleIcon
^^^^^^^^^^^^^

.. java:method:: @Override public BundleIcon getBundleIcon(long bundleId)
   :outertype: ModuleAdminServiceImpl

getBundleInfo
^^^^^^^^^^^^^

.. java:method:: @Override public BundleInformation getBundleInfo(long bundleId)
   :outertype: ModuleAdminServiceImpl

getBundles
^^^^^^^^^^

.. java:method:: @Override public List<BundleInformation> getBundles()
   :outertype: ModuleAdminServiceImpl

installBundle
^^^^^^^^^^^^^

.. java:method:: @Override public BundleInformation installBundle(MultipartFile bundleFile)
   :outertype: ModuleAdminServiceImpl

installBundle
^^^^^^^^^^^^^

.. java:method:: @Override public BundleInformation installBundle(MultipartFile bundleFile, boolean startBundle)
   :outertype: ModuleAdminServiceImpl

installFromRepository
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public BundleInformation installFromRepository(String featureId, boolean start)
   :outertype: ModuleAdminServiceImpl

restartBundle
^^^^^^^^^^^^^

.. java:method:: @Override public BundleInformation restartBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminServiceImpl

startBundle
^^^^^^^^^^^

.. java:method:: @Override public BundleInformation startBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminServiceImpl

stopBundle
^^^^^^^^^^

.. java:method:: @Override public BundleInformation stopBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminServiceImpl

uninstallBundle
^^^^^^^^^^^^^^^

.. java:method:: @Override public void uninstallBundle(long bundleId, boolean removeConfig) throws BundleException
   :outertype: ModuleAdminServiceImpl

