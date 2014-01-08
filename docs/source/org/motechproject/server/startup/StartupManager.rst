.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.osgi.service.event Event

.. java:import:: org.osgi.service.event EventAdmin

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.annotation PostConstruct

.. java:import:: java.security MessageDigest

.. java:import:: java.security NoSuchAlgorithmException

.. java:import:: java.util Arrays

.. java:import:: java.util Map

StartupManager
==============

.. java:package:: org.motechproject.server.startup
   :noindex:

.. java:type:: @Component public class StartupManager

   StartupManager controlling and managing the application loading

Methods
-------
canLaunchBundles
^^^^^^^^^^^^^^^^

.. java:method:: public boolean canLaunchBundles()
   :outertype: StartupManager

getDefaultSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: public SettingsRecord getDefaultSettings()
   :outertype: StartupManager

   This function is only called when the default configuration is loaded and is no config in the database or external files

isBootstrapConfigRequired
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isBootstrapConfigRequired()
   :outertype: StartupManager

isConfigRequired
^^^^^^^^^^^^^^^^

.. java:method:: public boolean isConfigRequired()
   :outertype: StartupManager

startup
^^^^^^^

.. java:method:: @PostConstruct public void startup()
   :outertype: StartupManager

