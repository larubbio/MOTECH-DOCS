.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io.filefilter TrueFileFilter

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.apache.commons.lang.builder HashCodeBuilder

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.core.filters ConfigFileFilter

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.core.io UrlResource

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.net MalformedURLException

.. java:import:: java.util Collection

.. java:import:: java.util List

ConfigLocation.FileAccessType
=============================

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public static enum FileAccessType
   :outertype: ConfigLocation

   Defines the access check required.

Enum Constants
--------------
READABLE
^^^^^^^^

.. java:field:: public static final ConfigLocation.FileAccessType READABLE
   :outertype: ConfigLocation.FileAccessType

WRITABLE
^^^^^^^^

.. java:field:: public static final ConfigLocation.FileAccessType WRITABLE
   :outertype: ConfigLocation.FileAccessType

