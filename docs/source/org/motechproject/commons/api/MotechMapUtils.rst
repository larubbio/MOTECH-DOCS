.. java:import:: java.util LinkedHashMap

.. java:import:: java.util Map

MotechMapUtils
==============

.. java:package:: org.motechproject.commons.api
   :noindex:

.. java:type:: public final class MotechMapUtils

   The \ ``MotechMapUtils``\  class contains methods that allow modifications and operations on maps

Methods
-------
mergeMaps
^^^^^^^^^

.. java:method:: public static Map<Object, Object> mergeMaps(Map<Object, Object> overridingMap, Map<Object, Object> baseMap)
   :outertype: MotechMapUtils

   Null-safe merge of two maps. If both parameters are null it returns empty map. If one of the maps is null, it returns the other one. If a key is present in two maps, the value in the merged map will be taken from the overriding map.

   :param overridingMap: The map overriding values in the base map
   :param baseMap: The base map
   :return: merged map

