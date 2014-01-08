.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.springframework.aop.framework Advised

.. java:import:: org.springframework.aop.support AopUtils

.. java:import:: java.util ArrayList

.. java:import:: java.util Dictionary

.. java:import:: java.util List

ExtendedBundleInformation
=========================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: public class ExtendedBundleInformation extends BundleInformation

   Extended version of the \ :java:ref:`BundleInformation`\  class, which adds more fields from the bundle's manifest. This class can be used to generate detailed views describing the given @{link Bundle}.

Fields
------
BUILD_JDK
^^^^^^^^^

.. java:field:: public static final String BUILD_JDK
   :outertype: ExtendedBundleInformation

BUILT_BY
^^^^^^^^

.. java:field:: public static final String BUILT_BY
   :outertype: ExtendedBundleInformation

BUNDLE_ACTIVATOR
^^^^^^^^^^^^^^^^

.. java:field:: public static final String BUNDLE_ACTIVATOR
   :outertype: ExtendedBundleInformation

CREATED_BY
^^^^^^^^^^

.. java:field:: public static final String CREATED_BY
   :outertype: ExtendedBundleInformation

DESCRIPTION
^^^^^^^^^^^

.. java:field:: public static final String DESCRIPTION
   :outertype: ExtendedBundleInformation

DOC_URL
^^^^^^^

.. java:field:: public static final String DOC_URL
   :outertype: ExtendedBundleInformation

EXPORT_PACKAGE
^^^^^^^^^^^^^^

.. java:field:: public static final String EXPORT_PACKAGE
   :outertype: ExtendedBundleInformation

IMPORT_PACKAGE
^^^^^^^^^^^^^^

.. java:field:: public static final String IMPORT_PACKAGE
   :outertype: ExtendedBundleInformation

LAST_MODIFIED
^^^^^^^^^^^^^

.. java:field:: public static final String LAST_MODIFIED
   :outertype: ExtendedBundleInformation

TOOL
^^^^

.. java:field:: public static final String TOOL
   :outertype: ExtendedBundleInformation

VENDOR
^^^^^^

.. java:field:: public static final String VENDOR
   :outertype: ExtendedBundleInformation

Constructors
------------
ExtendedBundleInformation
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ExtendedBundleInformation(Bundle bundle)
   :outertype: ExtendedBundleInformation

Methods
-------
getBuildJDK
^^^^^^^^^^^

.. java:method:: public String getBuildJDK()
   :outertype: ExtendedBundleInformation

getBuiltBy
^^^^^^^^^^

.. java:method:: public String getBuiltBy()
   :outertype: ExtendedBundleInformation

getBundleActivator
^^^^^^^^^^^^^^^^^^

.. java:method:: public String getBundleActivator()
   :outertype: ExtendedBundleInformation

getBundleExports
^^^^^^^^^^^^^^^^

.. java:method:: public List<PackageInfo> getBundleExports()
   :outertype: ExtendedBundleInformation

getBundleImports
^^^^^^^^^^^^^^^^

.. java:method:: public List<PackageInfo> getBundleImports()
   :outertype: ExtendedBundleInformation

getCreatedBy
^^^^^^^^^^^^

.. java:method:: public String getCreatedBy()
   :outertype: ExtendedBundleInformation

getDescription
^^^^^^^^^^^^^^

.. java:method:: public String getDescription()
   :outertype: ExtendedBundleInformation

getDocURL
^^^^^^^^^

.. java:method:: public String getDocURL()
   :outertype: ExtendedBundleInformation

getExportPackageHeader
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getExportPackageHeader()
   :outertype: ExtendedBundleInformation

getImportPackageHeader
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getImportPackageHeader()
   :outertype: ExtendedBundleInformation

getLastModified
^^^^^^^^^^^^^^^

.. java:method:: public DateTime getLastModified()
   :outertype: ExtendedBundleInformation

getRegisteredServices
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getRegisteredServices()
   :outertype: ExtendedBundleInformation

getServicesInUse
^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getServicesInUse()
   :outertype: ExtendedBundleInformation

getTool
^^^^^^^

.. java:method:: public String getTool()
   :outertype: ExtendedBundleInformation

getVendor
^^^^^^^^^

.. java:method:: public String getVendor()
   :outertype: ExtendedBundleInformation

setBundleExports
^^^^^^^^^^^^^^^^

.. java:method:: public void setBundleExports(List<PackageInfo> bundleExports)
   :outertype: ExtendedBundleInformation

setBundleImports
^^^^^^^^^^^^^^^^

.. java:method:: public void setBundleImports(List<PackageInfo> bundleImports)
   :outertype: ExtendedBundleInformation

