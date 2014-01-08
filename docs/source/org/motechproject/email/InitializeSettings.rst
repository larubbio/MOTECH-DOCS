.. java:import:: org.motechproject.email.model SettingsDto

.. java:import:: org.motechproject.email.service.impl PurgeEmailEventHandlerImpl

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.scheduler MotechSchedulerService

.. java:import:: org.motechproject.scheduler.domain CronSchedulableJob

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: java.util HashMap

.. java:import:: java.util Map

InitializeSettings
==================

.. java:package:: org.motechproject.email
   :noindex:

.. java:type:: public class InitializeSettings

   The \ ``InitializeSettings``\  class is responsible for handling changes in mail purging settings and adjusting/deleting the scheduler job responsible for it, in case the settings were changed

Constructors
------------
InitializeSettings
^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public InitializeSettings(SettingsFacade settingsFacade, MotechSchedulerService motechSchedulerService)
   :outertype: InitializeSettings

InitializeSettings
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public InitializeSettings()
   :outertype: InitializeSettings

Methods
-------
handleSettingsChange
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void handleSettingsChange()
   :outertype: InitializeSettings

