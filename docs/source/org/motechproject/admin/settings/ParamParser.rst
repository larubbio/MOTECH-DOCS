.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Properties

ParamParser
===========

.. java:package:: org.motechproject.admin.settings
   :noindex:

.. java:type:: public final class ParamParser

Methods
-------
constructProperties
^^^^^^^^^^^^^^^^^^^

.. java:method:: public static Properties constructProperties(Settings bundleSettings)
   :outertype: ParamParser

convertName
^^^^^^^^^^^

.. java:method:: public static void convertName(SettingsOption option)
   :outertype: ParamParser

convertNames
^^^^^^^^^^^^

.. java:method:: public static void convertNames(List<SettingsOption> options)
   :outertype: ParamParser

parseParam
^^^^^^^^^^

.. java:method:: public static SettingsOption parseParam(String key, Object value)
   :outertype: ParamParser

parseProperties
^^^^^^^^^^^^^^^

.. java:method:: public static List<SettingsOption> parseProperties(Properties props)
   :outertype: ParamParser

