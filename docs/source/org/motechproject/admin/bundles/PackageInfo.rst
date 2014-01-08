.. java:import:: org.osgi.service.packageadmin ExportedPackage

.. java:import:: java.util Objects

PackageInfo
===========

.. java:package:: org.motechproject.admin.bundles
   :noindex:

.. java:type:: public class PackageInfo

   A class representing a bundle import within the OSGi framework. Contains information about the exporter, the importer and the package name itself.

Constructors
------------
PackageInfo
^^^^^^^^^^^

.. java:constructor:: public PackageInfo(ExportedPackage exportedPackage)
   :outertype: PackageInfo

PackageInfo
^^^^^^^^^^^

.. java:constructor:: public PackageInfo(String name, String from, String version)
   :outertype: PackageInfo

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: PackageInfo

getFrom
^^^^^^^

.. java:method:: public String getFrom()
   :outertype: PackageInfo

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: PackageInfo

getVersion
^^^^^^^^^^

.. java:method:: public String getVersion()
   :outertype: PackageInfo

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: PackageInfo

setFrom
^^^^^^^

.. java:method:: public void setFrom(String from)
   :outertype: PackageInfo

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: PackageInfo

setVersion
^^^^^^^^^^

.. java:method:: public void setVersion(String version)
   :outertype: PackageInfo

