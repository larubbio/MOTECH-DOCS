.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.osgi.framework Bundle

.. java:import:: java.util ArrayList

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util TreeMap

ModuleRegistrationData
======================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class ModuleRegistrationData

   Object used to registered a module withing the Motech UI system. Represents a module and is used for building the common user interface. All modules that wish to register within the UI system must either expose this class as a spring bean in their application context or manually register it through the \ :java:ref:`UIFrameworkService`\  OSGi service.

Constructors
------------
ModuleRegistrationData
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModuleRegistrationData()
   :outertype: ModuleRegistrationData

ModuleRegistrationData
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModuleRegistrationData(String moduleName, String url, List<String> angularModules, Map<String, String> i18n, Header header)
   :outertype: ModuleRegistrationData

ModuleRegistrationData
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModuleRegistrationData(String moduleName, String url)
   :outertype: ModuleRegistrationData

ModuleRegistrationData
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModuleRegistrationData(String moduleName, Map<String, String> i18n)
   :outertype: ModuleRegistrationData

Methods
-------
addAngularModule
^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void addAngularModule(String moduleName)
   :outertype: ModuleRegistrationData

addI18N
^^^^^^^

.. java:method:: @JsonIgnore public void addI18N(String fileName, String fileLocation)
   :outertype: ModuleRegistrationData

addSubMenu
^^^^^^^^^^

.. java:method:: @JsonIgnore public void addSubMenu(String url, String label)
   :outertype: ModuleRegistrationData

addSubMenu
^^^^^^^^^^

.. java:method:: @JsonIgnore public void addSubMenu(String url, String label, String roleForAccess)
   :outertype: ModuleRegistrationData

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: ModuleRegistrationData

getAngularModules
^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getAngularModules()
   :outertype: ModuleRegistrationData

getAngularModulesStr
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getAngularModulesStr()
   :outertype: ModuleRegistrationData

getBundle
^^^^^^^^^

.. java:method:: @JsonIgnore public Bundle getBundle()
   :outertype: ModuleRegistrationData

getCriticalMessage
^^^^^^^^^^^^^^^^^^

.. java:method:: public String getCriticalMessage()
   :outertype: ModuleRegistrationData

getHeader
^^^^^^^^^

.. java:method:: public String getHeader()
   :outertype: ModuleRegistrationData

getI18n
^^^^^^^

.. java:method:: @JsonIgnore public Map<String, String> getI18n()
   :outertype: ModuleRegistrationData

getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: ModuleRegistrationData

getRoleForAccess
^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getRoleForAccess()
   :outertype: ModuleRegistrationData

getSettingsURL
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public String getSettingsURL()
   :outertype: ModuleRegistrationData

getSubMenu
^^^^^^^^^^

.. java:method:: public Map<String, SubmenuInfo> getSubMenu()
   :outertype: ModuleRegistrationData

getUrl
^^^^^^

.. java:method:: public String getUrl()
   :outertype: ModuleRegistrationData

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ModuleRegistrationData

isNeedsAttention
^^^^^^^^^^^^^^^^

.. java:method:: public boolean isNeedsAttention()
   :outertype: ModuleRegistrationData

removeAngularModule
^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void removeAngularModule(String moduleName)
   :outertype: ModuleRegistrationData

setBundle
^^^^^^^^^

.. java:method:: @JsonIgnore public void setBundle(Bundle bundle)
   :outertype: ModuleRegistrationData

setCriticalMessage
^^^^^^^^^^^^^^^^^^

.. java:method:: public void setCriticalMessage(String criticalMessage)
   :outertype: ModuleRegistrationData

setHeader
^^^^^^^^^

.. java:method:: public void setHeader(String header)
   :outertype: ModuleRegistrationData

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: ModuleRegistrationData

setNeedsAttention
^^^^^^^^^^^^^^^^^

.. java:method:: public void setNeedsAttention(boolean needsAttention)
   :outertype: ModuleRegistrationData

setRoleForAccess
^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setRoleForAccess(String role)
   :outertype: ModuleRegistrationData

setSettingsURL
^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void setSettingsURL(String settingsURL)
   :outertype: ModuleRegistrationData

setSubMenu
^^^^^^^^^^

.. java:method:: public void setSubMenu(Map<String, SubmenuInfo> subMenu)
   :outertype: ModuleRegistrationData

setUrl
^^^^^^

.. java:method:: public void setUrl(String url)
   :outertype: ModuleRegistrationData

subMenuNeedsAttention
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void subMenuNeedsAttention(String submenu)
   :outertype: ModuleRegistrationData

submenuBackToNormal
^^^^^^^^^^^^^^^^^^^

.. java:method:: @JsonIgnore public void submenuBackToNormal(String submenu)
   :outertype: ModuleRegistrationData

