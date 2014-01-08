.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.motechproject.config.core.service CoreConfigurationService

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.osgi.service.event Event

.. java:import:: org.osgi.service.event EventAdmin

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.core.io ResourceLoader

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.security DigestInputStream

.. java:import:: java.security MessageDigest

.. java:import:: java.security NoSuchAlgorithmException

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

ConfigLoader
============

.. java:package:: org.motechproject.server.config.service
   :noindex:

.. java:type:: @Component public class ConfigLoader

   Config loader used to load the platform core settings.

Methods
-------
findExistingConfigs
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<File> findExistingConfigs() throws IOException
   :outertype: ConfigLoader

   Finds all configs from the config location

loadDefaultConfig
^^^^^^^^^^^^^^^^^

.. java:method:: public SettingsRecord loadDefaultConfig()
   :outertype: ConfigLoader

loadMotechSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: public SettingsRecord loadMotechSettings()
   :outertype: ConfigLoader

setCoreConfigurationService
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Autowired public void setCoreConfigurationService(CoreConfigurationService coreConfigurationService)
   :outertype: ConfigLoader

setEventAdmin
^^^^^^^^^^^^^

.. java:method:: @Autowired public void setEventAdmin(EventAdmin eventAdmin)
   :outertype: ConfigLoader

setResourceLoader
^^^^^^^^^^^^^^^^^

.. java:method:: @Autowired public void setResourceLoader(ResourceLoader resourceLoader)
   :outertype: ConfigLoader

