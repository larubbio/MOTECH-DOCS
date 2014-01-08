.. java:import:: org.motechproject.admin.bundles ExtendedBundleInformation

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: java.util List

ModuleAdminService
==================

.. java:package:: org.motechproject.admin.service
   :noindex:

.. java:type:: public interface ModuleAdminService

   Service used by the view layer to manage bundles in the system. Supports retrieval of bundle information, managing bundle state, bundle installation/uninstallation, etc. Adequate admin permissions are required to use methods from this service.

Methods
-------
changeMaxUploadSize
^^^^^^^^^^^^^^^^^^^

.. java:method::  void changeMaxUploadSize(MotechEvent event)
   :outertype: ModuleAdminService

   Changes the max upload size allowed for bundles.

   :param event: the \ :java:ref:`MotechEvent`\  indicating the configuration change.

getBundleDetails
^^^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  ExtendedBundleInformation getBundleDetails(long bundleId)
   :outertype: ModuleAdminService

   Retrieves detailed information about the given bundle.

   :param bundleId: the bundle id of the bundle for which the information should be retrieved.
   :return: an \ :java:ref:`org.motechproject.admin.bundles.ExtendedBundleInformation`\  object containing detailed information about the given bundle.

getBundleIcon
^^^^^^^^^^^^^

.. java:method::  BundleIcon getBundleIcon(long bundleId)
   :outertype: ModuleAdminService

   Retrieves a \ :java:ref:`org.motechproject.server.api.BundleIcon`\  for the bundle with the given bundle id. The icon is loaded from the bundle.

   :param bundleId: the bundle id of the bundle for which the icon should be retrieved.
   :return: the icon retrieved for the bundle. If no icon is available, the default icon is returned.

getBundleInfo
^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation getBundleInfo(long bundleId)
   :outertype: ModuleAdminService

   Retrieves information for a bundle with a given bundle id.

   :param bundleId: the id of the bundle given by the OSGi framework.
   :return: a \ :java:ref:`BundleInformation`\  object encapsulating bundle details.

getBundles
^^^^^^^^^^

.. java:method:: @PreAuthorize  List<BundleInformation> getBundles()
   :outertype: ModuleAdminService

   Retrieves a list of Motech module bundles. Platform bundles required for operation and 3rd party bundles will be hidden from this view.

   :return: a list of \ :java:ref:`BundleInformation`\  objects representing Motech modules in the system.

installBundle
^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation installBundle(MultipartFile bundleFile)
   :outertype: ModuleAdminService

   Installs a bundle in the system. The installed bundle is then automatically started. Used to install uploaded bundles. This does not install any dependencies.

   :param bundleFile: the \ :java:ref:`MultipartFile`\  which should be the actual bundle jar.
   :return: the \ :java:ref:`BundleInformation`\  for the newly installed bundle.

installBundle
^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation installBundle(MultipartFile bundleFile, boolean startBundle)
   :outertype: ModuleAdminService

   Installs a bundle in the system. Used to install uploaded bundles. This does not install any dependencies.

   :param bundleFile: the \ :java:ref:`MultipartFile`\  which should be the actual bundle jar.
   :param startBundle: whether the bundle should be started after installation.
   :return: the \ :java:ref:`BundleInformation`\  for the newly installed bundle.

installFromRepository
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation installFromRepository(String featureId, boolean start)
   :outertype: ModuleAdminService

   Installs a feature(module) in the system using the Nexus repository. The requested bundle is downloaded and installed, and so are its dependencies.

   :param featureId: the id of the feature to be downloaded and installed.
   :param start: whether the module should be started after installation.
   :return: the \ :java:ref:`BundleInformation`\  for the newly installed bundle

restartBundle
^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation restartBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminService

   Restarts the bundle with the given bundle id. This is a shorthand for stopping and then starting a bundle.

   :param bundleId: the id of the bundle that should be restarted.
   :return: a \ :java:ref:`BundleInformation`\  object encapsulating the restarted bundle details.

startBundle
^^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation startBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminService

   Starts the bundle with the given bundle id.

   :param bundleId: the id of the bundle that should be started.
   :return: a \ :java:ref:`BundleInformation`\  object encapsulating the started bundle details.

stopBundle
^^^^^^^^^^

.. java:method:: @PreAuthorize  BundleInformation stopBundle(long bundleId) throws BundleException
   :outertype: ModuleAdminService

   Stops a bundle with the given bundle id.

   :param bundleId: the id of the bundle that should be stopped.
   :return: a \ :java:ref:`BundleInformation`\  object encapsulating the stopped bundle details.

uninstallBundle
^^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  void uninstallBundle(long bundleId, boolean removeConfig) throws BundleException
   :outertype: ModuleAdminService

   Uninstalls the bundle with the given bundle id from the system. The bundle file is also physically removed.

   :param bundleId: the id of the bundle that should be uninstalled.
   :param removeConfig: true if config file for bundle should be removed

