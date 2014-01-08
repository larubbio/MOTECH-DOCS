.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.service.packageadmin ExportedPackage

.. java:import:: org.osgi.service.packageadmin PackageAdmin

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ImportExportResolver
====================

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: @Component public class ImportExportResolver

   A class responsible for resolving \ :java:ref:`Bundle`\  imports and exports. It fills up \ :java:ref:`ExtendedBundleInformation`\  objects with additional information regarding \ :java:ref:`Bundle`\ 's imports and exports. This information gives better insight into the current state of the OSGi framework.

Methods
-------
refreshPackage
^^^^^^^^^^^^^^

.. java:method:: public void refreshPackage(Bundle bundle)
   :outertype: ImportExportResolver

resolveBundleWiring
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void resolveBundleWiring(ExtendedBundleInformation bundleInfo)
   :outertype: ImportExportResolver

   Resolves the bundle wiring for the bundle represented by \ :java:ref:`ExtendedBundleInformation`\  by creating \ :java:ref:`PackageInfo`\  objects. These objects represent an OSGi import containing information about both of the involved parties - the importer and the exporter.

   :param bundleInfo: the object representing the bundle, it will be filled with the import information. The bundle is resolved based on the bundle ID returned by \ :java:ref:`org.motechproject.admin.bundles.ExtendedBundleInformation.getBundleId()`\

