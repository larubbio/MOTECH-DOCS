.. java:import:: org.motechproject.config.core MotechConfigurationException

ConfigSource
============

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public final class ConfigSource

   Represents the source from which MOTECH configuration should be read.

Fields
------
FILE
^^^^

.. java:field:: public static final ConfigSource FILE
   :outertype: ConfigSource

UI
^^

.. java:field:: public static final ConfigSource UI
   :outertype: ConfigSource

Methods
-------
getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: ConfigSource

isFile
^^^^^^

.. java:method:: public boolean isFile()
   :outertype: ConfigSource

isValid
^^^^^^^

.. java:method:: public static boolean isValid(String name)
   :outertype: ConfigSource

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ConfigSource

valueOf
^^^^^^^

.. java:method:: public static ConfigSource valueOf(String name)
   :outertype: ConfigSource

