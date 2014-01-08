.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: java.util List

.. java:import:: java.util Objects

Loggers
=======

.. java:package:: org.motechproject.osgi.web.settings
   :noindex:

.. java:type:: public class Loggers

   Loggers class that holds information about all loggers in our system.

Constructors
------------
Loggers
^^^^^^^

.. java:constructor:: public Loggers()
   :outertype: Loggers

Loggers
^^^^^^^

.. java:constructor:: public Loggers(List<LogMapping> loggers, LogMapping root)
   :outertype: Loggers

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Loggers

getLoggers
^^^^^^^^^^

.. java:method:: public List<LogMapping> getLoggers()
   :outertype: Loggers

getRoot
^^^^^^^

.. java:method:: public LogMapping getRoot()
   :outertype: Loggers

getTrash
^^^^^^^^

.. java:method:: public List<LogMapping> getTrash()
   :outertype: Loggers

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Loggers

setLoggers
^^^^^^^^^^

.. java:method:: public void setLoggers(List<LogMapping> loggers)
   :outertype: Loggers

setRoot
^^^^^^^

.. java:method:: public void setRoot(LogMapping root)
   :outertype: Loggers

setTrash
^^^^^^^^

.. java:method:: public void setTrash(List<LogMapping> trash)
   :outertype: Loggers

