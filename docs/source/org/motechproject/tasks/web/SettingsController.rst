.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.tasks.domain SettingsDto

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

SettingsController
==================

.. java:package:: org.motechproject.tasks.web
   :noindex:

.. java:type:: @Controller public class SettingsController

Constructors
------------
SettingsController
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SettingsController(SettingsFacade settingsFacade)
   :outertype: SettingsController

Methods
-------
getSettings
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public SettingsDto getSettings()
   :outertype: SettingsController

saveSettings
^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveSettings(SettingsDto settings) throws BundleException
   :outertype: SettingsController

