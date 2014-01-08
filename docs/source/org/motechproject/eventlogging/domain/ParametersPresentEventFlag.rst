.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.util Collections

.. java:import:: java.util Map

ParametersPresentEventFlag
==========================

.. java:package:: org.motechproject.eventlogging.domain
   :noindex:

.. java:type:: public class ParametersPresentEventFlag implements EventFlag

Constructors
------------
ParametersPresentEventFlag
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ParametersPresentEventFlag()
   :outertype: ParametersPresentEventFlag

ParametersPresentEventFlag
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ParametersPresentEventFlag(Map<String, String> keyValuePairsPresent)
   :outertype: ParametersPresentEventFlag

Methods
-------
getKeyValuePairsPresent
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public Map<String, String> getKeyValuePairsPresent()
   :outertype: ParametersPresentEventFlag

passesFlags
^^^^^^^^^^^

.. java:method:: @Override public boolean passesFlags(MotechEvent eventToLog)
   :outertype: ParametersPresentEventFlag

setKeyValuePairsPresent
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setKeyValuePairsPresent(Map<String, String> keyValuePairsPresent)
   :outertype: ParametersPresentEventFlag

