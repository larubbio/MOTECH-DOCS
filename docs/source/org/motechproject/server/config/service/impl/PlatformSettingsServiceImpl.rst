.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.config.repository AllSettings

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.motechproject.server.config.service PlatformSettingsService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util Properties

PlatformSettingsServiceImpl
===========================

.. java:package:: org.motechproject.server.config.service.impl
   :noindex:

.. java:type:: @Service public class PlatformSettingsServiceImpl implements PlatformSettingsService

   Implementation of {@Link PlatformSettingsService} class for main motech settings managment

Methods
-------
exportPlatformSettings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Properties exportPlatformSettings()
   :outertype: PlatformSettingsServiceImpl

