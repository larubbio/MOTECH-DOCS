.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.io IOException

.. java:import:: java.util Properties

ConfigurationServiceIT
======================

.. java:package:: org.motechproject.config.service.impl
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class ConfigurationServiceIT

Methods
-------
shouldPersistAndRetrieveBundlePropertiesFromDatabase
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldPersistAndRetrieveBundlePropertiesFromDatabase() throws IOException, InterruptedException
   :outertype: ConfigurationServiceIT

shouldSaveBootstrapConfigToDefaultLocationAndLoadFromTheSameLocation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSaveBootstrapConfigToDefaultLocationAndLoadFromTheSameLocation()
   :outertype: ConfigurationServiceIT

