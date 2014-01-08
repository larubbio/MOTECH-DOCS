.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: org.codehaus.jackson.annotate JsonIgnoreProperties

.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Objects

DataSource.Lookup
=================

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public static class Lookup implements Serializable
   :outertype: DataSource

Constructors
------------
Lookup
^^^^^^

.. java:constructor:: public Lookup()
   :outertype: DataSource.Lookup

Lookup
^^^^^^

.. java:constructor:: public Lookup(String field, String value)
   :outertype: DataSource.Lookup

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: DataSource.Lookup

getField
^^^^^^^^

.. java:method:: public String getField()
   :outertype: DataSource.Lookup

getValue
^^^^^^^^

.. java:method:: public String getValue()
   :outertype: DataSource.Lookup

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: DataSource.Lookup

setField
^^^^^^^^

.. java:method:: public void setField(String field)
   :outertype: DataSource.Lookup

setValue
^^^^^^^^

.. java:method:: public void setValue(String value)
   :outertype: DataSource.Lookup

