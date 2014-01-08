.. java:import:: org.motechproject.mds.dto MdsSettingsDto

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

SettingsController
==================

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: @Controller public class SettingsController

   The \ ``SettingsController``\  is the Spring Framework Controller used by view layer for executing certain actions on module settings.

Methods
-------
export
^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void export(Object exportTable)
   :outertype: SettingsController

getSettings
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public MdsSettingsDto getSettings()
   :outertype: SettingsController

importData
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void importData(Object file)
   :outertype: SettingsController

saveSettings
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void saveSettings(MdsSettingsDto settings)
   :outertype: SettingsController

