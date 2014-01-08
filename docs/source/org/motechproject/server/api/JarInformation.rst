.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.util.jar Attributes

.. java:import:: java.util.jar JarFile

.. java:import:: java.util.jar Manifest

JarInformation
==============

.. java:package:: org.motechproject.server.api
   :noindex:

.. java:type:: public class JarInformation

Fields
------
BUNDLE_SYMBOLIC_NAME
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String BUNDLE_SYMBOLIC_NAME
   :outertype: JarInformation

BUNDLE_VERSION
^^^^^^^^^^^^^^

.. java:field:: public static final String BUNDLE_VERSION
   :outertype: JarInformation

EXTRACTION_FAILED
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String EXTRACTION_FAILED
   :outertype: JarInformation

IMPLEMENTATION_TITLE
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String IMPLEMENTATION_TITLE
   :outertype: JarInformation

IMPLEMENTATION_VENDOR_ID
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String IMPLEMENTATION_VENDOR_ID
   :outertype: JarInformation

IMPLEMENTATION_VERSION
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String IMPLEMENTATION_VERSION
   :outertype: JarInformation

Constructors
------------
JarInformation
^^^^^^^^^^^^^^

.. java:constructor:: public JarInformation(File file) throws IOException
   :outertype: JarInformation

Methods
-------
getBundleSymbolicName
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getBundleSymbolicName()
   :outertype: JarInformation

getBundleVersion
^^^^^^^^^^^^^^^^

.. java:method:: public String getBundleVersion()
   :outertype: JarInformation

getFilename
^^^^^^^^^^^

.. java:method:: public String getFilename()
   :outertype: JarInformation

getImplementationTitle
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getImplementationTitle()
   :outertype: JarInformation

getImplementationVendorID
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getImplementationVendorID()
   :outertype: JarInformation

getImplementationVersion
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getImplementationVersion()
   :outertype: JarInformation

getPath
^^^^^^^

.. java:method:: public String getPath()
   :outertype: JarInformation

