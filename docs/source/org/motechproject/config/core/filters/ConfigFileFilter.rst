.. java:import:: org.apache.commons.io FilenameUtils

.. java:import:: org.apache.commons.io.filefilter FileFileFilter

.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: java.io File

ConfigFileFilter
================

.. java:package:: org.motechproject.config.core.filters
   :noindex:

.. java:type:: public class ConfigFileFilter extends FileFileFilter

   FileFilter implementation to filter configuration files.

Fields
------
PLATFORM_CORE_CONFIG_FILTER
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final FileFileFilter PLATFORM_CORE_CONFIG_FILTER
   :outertype: ConfigFileFilter

Methods
-------
accept
^^^^^^

.. java:method:: @Override public boolean accept(File file)
   :outertype: ConfigFileFilter

isFileSupported
^^^^^^^^^^^^^^^

.. java:method:: public static boolean isFileSupported(File file)
   :outertype: ConfigFileFilter

isPlatformCoreConfigFile
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static boolean isPlatformCoreConfigFile(File file)
   :outertype: ConfigFileFilter

