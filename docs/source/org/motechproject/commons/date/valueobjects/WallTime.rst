.. java:import:: org.joda.time Period

.. java:import:: org.motechproject.commons.date.util JodaFormatter

.. java:import:: java.io Serializable

WallTime
========

.. java:package:: org.motechproject.commons.date.valueobjects
   :noindex:

.. java:type:: public class WallTime implements Serializable

Constructors
------------
WallTime
^^^^^^^^

.. java:constructor:: public WallTime(String userReadableForm)
   :outertype: WallTime

Methods
-------
asPeriod
^^^^^^^^

.. java:method:: public Period asPeriod()
   :outertype: WallTime

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: WallTime

getHours
^^^^^^^^

.. java:method:: public int getHours()
   :outertype: WallTime

getMinutes
^^^^^^^^^^

.. java:method:: public int getMinutes()
   :outertype: WallTime

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: WallTime

inDays
^^^^^^

.. java:method:: public int inDays()
   :outertype: WallTime

inMillis
^^^^^^^^

.. java:method:: public long inMillis()
   :outertype: WallTime

inMinutes
^^^^^^^^^

.. java:method:: public int inMinutes()
   :outertype: WallTime

isLessThanADay
^^^^^^^^^^^^^^

.. java:method:: public boolean isLessThanADay()
   :outertype: WallTime

