.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time MutablePeriod

.. java:import:: org.joda.time Period

.. java:import:: org.joda.time ReadWritablePeriod

.. java:import:: org.joda.time.format DateTimeFormatter

.. java:import:: org.joda.time.format ISODateTimeFormat

.. java:import:: org.joda.time.format PeriodFormatter

.. java:import:: org.joda.time.format PeriodFormatterBuilder

.. java:import:: org.joda.time.format PeriodParser

.. java:import:: org.motechproject.commons.date ParseException

.. java:import:: java.util Locale

JodaFormatter
=============

.. java:package:: org.motechproject.commons.date.util
   :noindex:

.. java:type:: public class JodaFormatter

Constructors
------------
JodaFormatter
^^^^^^^^^^^^^

.. java:constructor:: public JodaFormatter()
   :outertype: JodaFormatter

Methods
-------
formatDateTime
^^^^^^^^^^^^^^

.. java:method:: public String formatDateTime(DateTime dateTime)
   :outertype: JodaFormatter

formatPeriod
^^^^^^^^^^^^

.. java:method:: public String formatPeriod(Period period)
   :outertype: JodaFormatter

   Format joda period as text, eg: "1 year"

   :param period: time interval

parse
^^^^^

.. java:method:: public Period parse(String intervalString, Locale locale)
   :outertype: JodaFormatter

   Parse time interval in different units, eg: "1 year"

   :param intervalString: time interval format   number: integer unit : year, month, week, day, hour, minute, second (can use plural forms also) currently compound units like 1 year and 2 months are not supported

parseDateTime
^^^^^^^^^^^^^

.. java:method:: public DateTime parseDateTime(String isoDateTime)
   :outertype: JodaFormatter

parsePeriod
^^^^^^^^^^^

.. java:method:: public Period parsePeriod(String intervalString)
   :outertype: JodaFormatter

