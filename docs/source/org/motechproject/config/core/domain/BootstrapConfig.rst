.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.config.core MotechConfigurationException

BootstrapConfig
===============

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public class BootstrapConfig

   Represents the bootstrap configuration object. It is composed of:

   ..

   #. DBConfig - represents the database related bootstrap object.
   #. Tenant ID - represents the identifier of the tenant.
   #. Configuration source - represents the source of configuration (FILE / UI).

Fields
------
CONFIG_SOURCE
^^^^^^^^^^^^^

.. java:field:: public static final String CONFIG_SOURCE
   :outertype: BootstrapConfig

DB_PASSWORD
^^^^^^^^^^^

.. java:field:: public static final String DB_PASSWORD
   :outertype: BootstrapConfig

DB_URL
^^^^^^

.. java:field:: public static final String DB_URL
   :outertype: BootstrapConfig

DB_USERNAME
^^^^^^^^^^^

.. java:field:: public static final String DB_USERNAME
   :outertype: BootstrapConfig

DEFAULT_TENANT_ID
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DEFAULT_TENANT_ID
   :outertype: BootstrapConfig

TENANT_ID
^^^^^^^^^

.. java:field:: public static final String TENANT_ID
   :outertype: BootstrapConfig

Constructors
------------
BootstrapConfig
^^^^^^^^^^^^^^^

.. java:constructor:: public BootstrapConfig(DBConfig dbConfig, String tenantId, ConfigSource configSource)
   :outertype: BootstrapConfig

   :param dbConfig:
   :param tenantId:
   :param configSource:

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: BootstrapConfig

getConfigSource
^^^^^^^^^^^^^^^

.. java:method:: public ConfigSource getConfigSource()
   :outertype: BootstrapConfig

getDbConfig
^^^^^^^^^^^

.. java:method:: public DBConfig getDbConfig()
   :outertype: BootstrapConfig

getTenantId
^^^^^^^^^^^

.. java:method:: public String getTenantId()
   :outertype: BootstrapConfig

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: BootstrapConfig

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: BootstrapConfig

