.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web SubmenuInfo

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.ui.comparator IndividualsComparator

.. java:import:: org.motechproject.server.ui.ex AlreadyRegisteredException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util Collection

.. java:import:: java.util HashMap

.. java:import:: java.util Map

.. java:import:: java.util TreeMap

UIFrameworkServiceImpl
======================

.. java:package:: org.motechproject.server.ui.impl
   :noindex:

.. java:type:: @Service public class UIFrameworkServiceImpl implements UIFrameworkService

   Implementation of the \ :java:ref:`UIFrameworkService`\  interface. Stores the registered \ :java:ref:`ModuleRegistrationData`\  in memory.

Methods
-------
getModuleData
^^^^^^^^^^^^^

.. java:method:: @Override public ModuleRegistrationData getModuleData(String moduleName)
   :outertype: UIFrameworkServiceImpl

getModuleDataByBundle
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ModuleRegistrationData getModuleDataByBundle(Bundle bundle)
   :outertype: UIFrameworkServiceImpl

getRegisteredModules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Map<String, Collection<ModuleRegistrationData>> getRegisteredModules()
   :outertype: UIFrameworkServiceImpl

isModuleRegistered
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean isModuleRegistered(String moduleName)
   :outertype: UIFrameworkServiceImpl

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleBackToNormal(String moduleName)
   :outertype: UIFrameworkServiceImpl

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleBackToNormal(String moduleName, String submenu)
   :outertype: UIFrameworkServiceImpl

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleNeedsAttention(String moduleName, String message)
   :outertype: UIFrameworkServiceImpl

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleNeedsAttention(String moduleName, String submenu, String message)
   :outertype: UIFrameworkServiceImpl

registerModule
^^^^^^^^^^^^^^

.. java:method:: @Override public void registerModule(ModuleRegistrationData module)
   :outertype: UIFrameworkServiceImpl

unregisterModule
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void unregisterModule(String moduleName)
   :outertype: UIFrameworkServiceImpl

