.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.io.filefilter TrueFileFilter

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io OutputStream

.. java:import:: java.net MalformedURLException

.. java:import:: java.net URL

.. java:import:: java.util Collection

BundleDirectoryManager
======================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: public class BundleDirectoryManager

   This class is responsible for saving/removing bundle files. Bundles are currently stored in a specified directory. Permanently uninstalling a bundle requires also its removal through this class. It is also responsible for saving new bundles coming either as a \ :java:ref:`MultipartFile`\ (UI) or an \ :java:ref:`InputStream`\ .

Methods
-------
getBundleDir
^^^^^^^^^^^^

.. java:method:: public String getBundleDir()
   :outertype: BundleDirectoryManager

   Returns the directory used to store Motech bundles

   :return: the bundle directory

removeBundle
^^^^^^^^^^^^

.. java:method:: public boolean removeBundle(Bundle bundle) throws MalformedURLException
   :outertype: BundleDirectoryManager

   Removes the given \ :java:ref:`Bundle`\  from the filesystem. The file to be removed is determined based on the return value of \ :java:ref:`org.osgi.framework.Bundle.getLocation()`\  from the passed bundle.

   :param bundle: the \ :java:ref:`Bundle`\  to be removed from the filesystem.
   :return: true if the bundle was removed, false otherwise.

retrieveAllFiles
^^^^^^^^^^^^^^^^

.. java:method:: public Collection<File> retrieveAllFiles()
   :outertype: BundleDirectoryManager

   Retrieves all \ :java:ref:`File`\ s from the currently set bundle directory.

   :return: a \ :java:ref:`Collection`\  of \ :java:ref:`File`\ s from the currently set bundle directory.

saveBundleFile
^^^^^^^^^^^^^^

.. java:method:: public File saveBundleFile(MultipartFile multipartFile) throws IOException
   :outertype: BundleDirectoryManager

   Saves a bundle from the given MultipartFile. The bundle is placed in the specified bundle directory. The \ ``MultipartFile``\  objects usually come from the UI(uploaded bundles).

   :param multipartFile: the file representing the bundle.
   :return: the \ :java:ref:`File`\  created in the filesystem.

saveBundleStreamToFile
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public File saveBundleStreamToFile(String destFileName, InputStream in) throws IOException
   :outertype: BundleDirectoryManager

   Saves a bundle from the given \ :java:ref:`InputStream`\ . The bundle is placed in the specified bundle directory. Since the inputstream does not contain a name, the name of the resultant file must also be provided.

   :param destFileName: the name of destination file to which the bundle will be saved.
   :param in: the \ :java:ref:`InputStream`\  containing the bundle
   :return: the \ :java:ref:`File`\  created in the filesystem.

setBundleDir
^^^^^^^^^^^^

.. java:method:: public void setBundleDir(String bundleDir)
   :outertype: BundleDirectoryManager

   Changes the directory used to store Motech bundles.

   :param bundleDir: the directory which is to be used for storing bundles.

