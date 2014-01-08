.. java:import:: org.motechproject.email InitializeSettings

.. java:import:: org.motechproject.email.constants EmailRolesConstants

.. java:import:: org.motechproject.email.model SettingsDto

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.mail.javamail JavaMailSenderImpl

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: java.io IOException

SettingsController
==================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: @Controller public class SettingsController

   The \ ``SettingsController``\  class is responsible for handling web requests, connected with settings in the Email module

Constructors
------------
SettingsController
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SettingsController(SettingsFacade settingsFacade, JavaMailSenderImpl mailSender, InitializeSettings initializeSettings)
   :outertype: SettingsController

SettingsController
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SettingsController()
   :outertype: SettingsController

Methods
-------
getSettings
^^^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseBody public SettingsDto getSettings()
   :outertype: SettingsController

handleException
^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleException(Exception e) throws IOException
   :outertype: SettingsController

setSettings
^^^^^^^^^^^

.. java:method:: @RequestMapping @PreAuthorize @ResponseStatus public void setSettings(SettingsDto settings)
   :outertype: SettingsController

