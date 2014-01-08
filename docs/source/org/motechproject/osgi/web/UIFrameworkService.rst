.. java:import:: org.osgi.framework Bundle

.. java:import:: java.util Collection

.. java:import:: java.util Map

UIFrameworkService
==================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public interface UIFrameworkService

   Service responsible for managing the interface. Provides methods for registering/un-registering modules. All modules are represented by \ :java:ref:`ModuleRegistrationData`\  objects, either registered directly through this service or automatically by exposing it in their spring context. This service also allows manipulation of module state, by marking given modules as requiring attention on the UI.

Fields
------
MODULES_WITHOUT_SUBMENU
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field::  String MODULES_WITHOUT_SUBMENU
   :outertype: UIFrameworkService

MODULES_WITHOUT_UI
^^^^^^^^^^^^^^^^^^

.. java:field::  String MODULES_WITHOUT_UI
   :outertype: UIFrameworkService

MODULES_WITH_SUBMENU
^^^^^^^^^^^^^^^^^^^^

.. java:field::  String MODULES_WITH_SUBMENU
   :outertype: UIFrameworkService

Methods
-------
getModuleData
^^^^^^^^^^^^^

.. java:method::  ModuleRegistrationData getModuleData(String moduleName)
   :outertype: UIFrameworkService

getModuleDataByBundle
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  ModuleRegistrationData getModuleDataByBundle(Bundle bundle)
   :outertype: UIFrameworkService

getRegisteredModules
^^^^^^^^^^^^^^^^^^^^

.. java:method::  Map<String, Collection<ModuleRegistrationData>> getRegisteredModules()
   :outertype: UIFrameworkService

isModuleRegistered
^^^^^^^^^^^^^^^^^^

.. java:method::  boolean isModuleRegistered(String moduleName)
   :outertype: UIFrameworkService

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method::  void moduleBackToNormal(String moduleName)
   :outertype: UIFrameworkService

moduleBackToNormal
^^^^^^^^^^^^^^^^^^

.. java:method::  void moduleBackToNormal(String moduleName, String submenu)
   :outertype: UIFrameworkService

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void moduleNeedsAttention(String moduleName, String message)
   :outertype: UIFrameworkService

moduleNeedsAttention
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void moduleNeedsAttention(String moduleName, String submenu, String message)
   :outertype: UIFrameworkService

registerModule
^^^^^^^^^^^^^^

.. java:method::  void registerModule(ModuleRegistrationData module)
   :outertype: UIFrameworkService

unregisterModule
^^^^^^^^^^^^^^^^

.. java:method::  void unregisterModule(String moduleName)
   :outertype: UIFrameworkService

