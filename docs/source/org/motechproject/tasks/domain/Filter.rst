.. java:import:: org.codehaus.jackson.annotate JsonIgnore

.. java:import:: java.io Serializable

.. java:import:: java.util Objects

Filter
======

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class Filter implements Serializable

Constructors
------------
Filter
^^^^^^

.. java:constructor:: public Filter()
   :outertype: Filter

Filter
^^^^^^

.. java:constructor:: public Filter(EventParameter eventParameter, boolean negationOperator, String operator, String expression)
   :outertype: Filter

Filter
^^^^^^

.. java:constructor:: public Filter(String displayName, String key, ParameterType type, boolean negationOperator, String operator, String expression)
   :outertype: Filter

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Filter

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: public String getDisplayName()
   :outertype: Filter

getEventParameter
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated @JsonIgnore public EventParameter getEventParameter()
   :outertype: Filter

getExpression
^^^^^^^^^^^^^

.. java:method:: public String getExpression()
   :outertype: Filter

getKey
^^^^^^

.. java:method:: public String getKey()
   :outertype: Filter

getOperator
^^^^^^^^^^^

.. java:method:: public String getOperator()
   :outertype: Filter

getType
^^^^^^^

.. java:method:: public ParameterType getType()
   :outertype: Filter

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Filter

isNegationOperator
^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isNegationOperator()
   :outertype: Filter

setDisplayName
^^^^^^^^^^^^^^

.. java:method:: public void setDisplayName(String displayName)
   :outertype: Filter

setEventParameter
^^^^^^^^^^^^^^^^^

.. java:method:: @Deprecated public void setEventParameter(EventParameter eventParameter)
   :outertype: Filter

setExpression
^^^^^^^^^^^^^

.. java:method:: public void setExpression(String expression)
   :outertype: Filter

setKey
^^^^^^

.. java:method:: public void setKey(String key)
   :outertype: Filter

setNegationOperator
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setNegationOperator(boolean negationOperator)
   :outertype: Filter

setOperator
^^^^^^^^^^^

.. java:method:: public void setOperator(String operator)
   :outertype: Filter

setType
^^^^^^^

.. java:method:: public void setType(ParameterType type)
   :outertype: Filter

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: Filter

