.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.junit Assert

.. java:import:: org.junit Test

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.server.ui.ex AlreadyRegisteredException

.. java:import:: org.motechproject.server.ui.impl UIFrameworkServiceImpl

.. java:import:: java.util Collection

.. java:import:: java.util Map

UIFrameworkServiceTest
======================

.. java:package:: org.motechproject.server.ui
   :noindex:

.. java:type:: public class UIFrameworkServiceTest

Fields
------
moduleRegistration
^^^^^^^^^^^^^^^^^^

.. java:field::  ModuleRegistrationData moduleRegistration
   :outertype: UIFrameworkServiceTest

service
^^^^^^^

.. java:field::  UIFrameworkService service
   :outertype: UIFrameworkServiceTest

Methods
-------
shouldCheckIfModuleRegistered
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldCheckIfModuleRegistered()
   :outertype: UIFrameworkServiceTest

shouldIgnoreNonExistentModules
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldIgnoreNonExistentModules()
   :outertype: UIFrameworkServiceTest

shouldSetAndUnsetAttentionNeededFlag
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSetAndUnsetAttentionNeededFlag()
   :outertype: UIFrameworkServiceTest

testDoubleRegistration
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testDoubleRegistration()
   :outertype: UIFrameworkServiceTest

testRegisterUnregisterModule
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterUnregisterModule()
   :outertype: UIFrameworkServiceTest

