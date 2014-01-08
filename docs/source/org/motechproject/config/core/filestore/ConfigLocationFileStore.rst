.. java:import:: org.apache.commons.configuration ConfigurationException

.. java:import:: org.apache.commons.configuration PropertiesConfiguration

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.domain ConfigLocation

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ConfigLocationFileStore
=======================

.. java:package:: org.motechproject.config.core.filestore
   :noindex:

.. java:type:: @Component public class ConfigLocationFileStore

   Used to read default platform config location(s) from \ ``config-location.properties``\  and also to save in the file in the default location.

   \ ``config-location.properties``\  file will be loaded according to the behaviour of \ :java:ref:`org.apache.commons.configuration.PropertiesConfiguration`\  as specified \ `here <http://commons.apache.org/proper/commons-configuration/userguide/howto_filebased.html#Specifying_the_file>`_\ .

Fields
------
CONFIG_LOCATION_PROPERTY_KEY
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String CONFIG_LOCATION_PROPERTY_KEY
   :outertype: ConfigLocationFileStore

Constructors
------------
ConfigLocationFileStore
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ConfigLocationFileStore(PropertiesConfiguration propertiesConfiguration)
   :outertype: ConfigLocationFileStore

Methods
-------
add
^^^

.. java:method:: public void add(String location)
   :outertype: ConfigLocationFileStore

getAll
^^^^^^

.. java:method:: public Iterable<ConfigLocation> getAll()
   :outertype: ConfigLocationFileStore

