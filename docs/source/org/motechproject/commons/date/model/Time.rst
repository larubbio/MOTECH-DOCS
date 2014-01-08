.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time LocalTime

.. java:import:: java.io Serializable

Time
====

.. java:package:: org.motechproject.commons.date.model
   :noindex:

.. java:type:: public class Time implements Comparable<Time>, Serializable

Constructors
------------
Time
^^^^

.. java:constructor:: public Time()
   :outertype: Time

Time
^^^^

.. java:constructor:: public Time(int hour, int minute)
   :outertype: Time

Time
^^^^

.. java:constructor:: public Time(Integer hour, Integer minute)
   :outertype: Time

Time
^^^^

.. java:constructor:: public Time(LocalTime localTime)
   :outertype: Time

Time
^^^^

.. java:constructor:: public Time(String timeStr)
   :outertype: Time

Methods
-------
compareTo
^^^^^^^^^

.. java:method:: @Override public int compareTo(Time otherTime)
   :outertype: Time

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Time

ge
^^

.. java:method:: public boolean ge(Time toCompare)
   :outertype: Time

getDateTime
^^^^^^^^^^^

.. java:method:: public DateTime getDateTime(DateTime dateTime)
   :outertype: Time

getHour
^^^^^^^

.. java:method:: public Integer getHour()
   :outertype: Time

getMinute
^^^^^^^^^

.. java:method:: public Integer getMinute()
   :outertype: Time

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Time

isBefore
^^^^^^^^

.. java:method:: public boolean isBefore(Time other)
   :outertype: Time

le
^^

.. java:method:: public boolean le(Time toCompare)
   :outertype: Time

parseTime
^^^^^^^^^

.. java:method:: public static Time parseTime(String time, String separator)
   :outertype: Time

setHour
^^^^^^^

.. java:method:: public void setHour(Integer hour)
   :outertype: Time

setMinute
^^^^^^^^^

.. java:method:: public void setMinute(Integer minute)
   :outertype: Time

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: Time

