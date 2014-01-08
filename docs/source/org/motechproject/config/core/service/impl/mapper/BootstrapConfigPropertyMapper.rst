.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.config.core.domain BootstrapConfig

.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.config.core.domain DBConfig

.. java:import:: java.util Properties

BootstrapConfigPropertyMapper
=============================

.. java:package:: org.motechproject.config.core.service.impl.mapper
   :noindex:

.. java:type:: public final class BootstrapConfigPropertyMapper

   This class provides static utility methods for Mapping between \ ``BootstrapConfig``\  and \ ``Properties``\

Methods
-------
fromProperties
^^^^^^^^^^^^^^

.. java:method:: public static BootstrapConfig fromProperties(Properties bootstrapProperties)
   :outertype: BootstrapConfigPropertyMapper

   Map from properties to BootstrapConfig object

   :param bootstrapProperties:
   :return: BootstrapConfig object mapped from provided properties.

toProperties
^^^^^^^^^^^^

.. java:method:: public static Properties toProperties(BootstrapConfig bootstrapConfig)
   :outertype: BootstrapConfigPropertyMapper

   Map from BootstrapConfig to Properties

   :param bootstrapConfig:
   :return: Properties mapped from provided bootstrapConfig.

