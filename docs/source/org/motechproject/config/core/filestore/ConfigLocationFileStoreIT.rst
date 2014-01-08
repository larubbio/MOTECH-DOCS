.. java:import:: org.apache.commons.configuration ConfigurationException

.. java:import:: org.apache.commons.configuration PropertiesConfiguration

.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.io IOException

.. java:import:: java.util Iterator

ConfigLocationFileStoreIT
=========================

.. java:package:: org.motechproject.config.core.filestore
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class ConfigLocationFileStoreIT

Methods
-------
shouldReadConfigLocations
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReadConfigLocations()
   :outertype: ConfigLocationFileStoreIT

shouldSubstituteHomeDirectoryInThePath
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldSubstituteHomeDirectoryInThePath() throws ConfigurationException, IOException
   :outertype: ConfigLocationFileStoreIT

