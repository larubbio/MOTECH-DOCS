.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.osgi.framework Bundle

.. java:import:: java.util Collection

.. java:import:: java.util Collections

.. java:import:: java.util Map

MockUIFrameworkService
======================

.. java:package:: org.motechproject.admin.osgi
   :noindex:

.. java:type:: public class MockUIFrameworkService implements UIFrameworkService

Methods
-------
getModuleData
^^^^^^^^^^^^^

.. java:method:: @Override public ModuleRegistrationData getModuleData(String moduleName)
   :outertype: MockUIFrameworkService

getModuleDataByBundle
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ModuleRegistrationData getModuleDataByBundle(Bundle bundle)
   :outertype: MockUIFrameworkService

getRegisteredModules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Map<String, Collection<ModuleRegistrationData>> getRegisteredModules()
   :outertype: MockUIFrameworkService

isModuleRegistered
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean isModuleRegistered(String moduleName)
   :outertype: MockUIFrameworkService

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleBackToNormal(String moduleName)
   :outertype: MockUIFrameworkService

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleBackToNormal(String moduleName, String submenu)
   :outertype: MockUIFrameworkService

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleNeedsAttention(String moduleName, String message)
   :outertype: MockUIFrameworkService

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void moduleNeedsAttention(String moduleName, String message, String submenu)
   :outertype: MockUIFrameworkService

registerModule
^^^^^^^^^^^^^^

.. java:method:: @Override public void registerModule(ModuleRegistrationData module)
   :outertype: MockUIFrameworkService

unregisterModule
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void unregisterModule(String moduleName)
   :outertype: MockUIFrameworkService

