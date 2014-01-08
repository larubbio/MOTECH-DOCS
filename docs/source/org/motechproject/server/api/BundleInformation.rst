.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework Version

.. java:import:: java.util Objects

BundleInformation
=================

.. java:package:: org.motechproject.server.api
   :noindex:

.. java:type:: public class BundleInformation

   Class acting as a DTO for a \ :java:ref:`Bundle`\  in the system.

Fields
------
BUNDLE_NAME
^^^^^^^^^^^

.. java:field:: protected static final String BUNDLE_NAME
   :outertype: BundleInformation

Constructors
------------
BundleInformation
^^^^^^^^^^^^^^^^^

.. java:constructor:: public BundleInformation(Bundle bundle)
   :outertype: BundleInformation

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object arg0)
   :outertype: BundleInformation

getBundleId
^^^^^^^^^^^

.. java:method:: public long getBundleId()
   :outertype: BundleInformation

getLocation
^^^^^^^^^^^

.. java:method:: public String getLocation()
   :outertype: BundleInformation

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: BundleInformation

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: BundleInformation

getSettingsURL
^^^^^^^^^^^^^^

.. java:method:: public String getSettingsURL()
   :outertype: BundleInformation

getState
^^^^^^^^

.. java:method:: public State getState()
   :outertype: BundleInformation

getSymbolicName
^^^^^^^^^^^^^^^

.. java:method:: public String getSymbolicName()
   :outertype: BundleInformation

getVersion
^^^^^^^^^^

.. java:method:: public Version getVersion()
   :outertype: BundleInformation

hasStatus
^^^^^^^^^

.. java:method:: public boolean hasStatus(int status)
   :outertype: BundleInformation

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: BundleInformation

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: BundleInformation

setSettingsURL
^^^^^^^^^^^^^^

.. java:method:: public void setSettingsURL(String settingsURL)
   :outertype: BundleInformation

