.. java:import:: java.util Map

DataProvider
============

.. java:package:: org.motechproject.commons.api
   :noindex:

.. java:type:: public interface DataProvider

Methods
-------
getName
^^^^^^^

.. java:method::  String getName()
   :outertype: DataProvider

lookup
^^^^^^

.. java:method::  Object lookup(String type, Map<String, String> lookupFields)
   :outertype: DataProvider

supports
^^^^^^^^

.. java:method::  boolean supports(String type)
   :outertype: DataProvider

toJSON
^^^^^^

.. java:method::  String toJSON()
   :outertype: DataProvider

