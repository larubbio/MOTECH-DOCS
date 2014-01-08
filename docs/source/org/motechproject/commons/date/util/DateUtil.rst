.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeFieldType

.. java:import:: org.joda.time DateTimeZone

.. java:import:: org.joda.time LocalDate

.. java:import:: org.joda.time LocalDateTime

.. java:import:: org.joda.time Period

.. java:import:: org.joda.time PeriodType

.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: java.util ArrayList

.. java:import:: java.util Date

.. java:import:: java.util List

DateUtil
========

.. java:package:: org.motechproject.commons.date.util
   :noindex:

.. java:type:: public final class DateUtil

Methods
-------
daysPast
^^^^^^^^

.. java:method:: public static int daysPast(LocalDate localDate, DayOfWeek dayOfWeek)
   :outertype: DateUtil

daysStarting
^^^^^^^^^^^^

.. java:method:: public static List<DayOfWeek> daysStarting(DayOfWeek day, int numberOfDays)
   :outertype: DateUtil

daysToCalendarWeekEnd
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static int daysToCalendarWeekEnd(LocalDate date, int calendarWeekStartDay)
   :outertype: DateUtil

endOfDay
^^^^^^^^

.. java:method:: public static DateTime endOfDay(Date dateTime)
   :outertype: DateUtil

getDifferenceOfDatesInYears
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static int getDifferenceOfDatesInYears(Date startDate)
   :outertype: DateUtil

greaterThanOrEqualTo
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static List<DateTime> greaterThanOrEqualTo(DateTime date, List<DateTime> dates)
   :outertype: DateUtil

inRange
^^^^^^^

.. java:method:: public static boolean inRange(DateTime reference, DateTime start, DateTime end)
   :outertype: DateUtil

isOnOrAfter
^^^^^^^^^^^

.. java:method:: public static boolean isOnOrAfter(DateTime firstDate, DateTime secondDate)
   :outertype: DateUtil

isOnOrBefore
^^^^^^^^^^^^

.. java:method:: public static boolean isOnOrBefore(DateTime firstDate, DateTime secondDate)
   :outertype: DateUtil

lessThan
^^^^^^^^

.. java:method:: public static List<DateTime> lessThan(DateTime date, List<DateTime> dates)
   :outertype: DateUtil

newDate
^^^^^^^

.. java:method:: public static LocalDate newDate(int year, int month, int day)
   :outertype: DateUtil

newDate
^^^^^^^

.. java:method:: public static LocalDate newDate(Date date)
   :outertype: DateUtil

newDate
^^^^^^^

.. java:method:: public static LocalDate newDate(DateTime dateTime)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(LocalDate localDate, int hour, int minute, int second)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(Date date)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(LocalDate date)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(LocalDate localDate, Time time)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(int year, int month, int day, Time time)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(int year, int month, int day)
   :outertype: DateUtil

newDateTime
^^^^^^^^^^^

.. java:method:: public static DateTime newDateTime(int year, int month, int day, int hour, int minute, int second)
   :outertype: DateUtil

nextApplicableWeekDay
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static DateTime nextApplicableWeekDay(DateTime fromDate, List<DayOfWeek> applicableDays)
   :outertype: DateUtil

nextApplicableWeekDayIncludingFromDate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static DateTime nextApplicableWeekDayIncludingFromDate(DateTime fromDate, List<DayOfWeek> applicableDays)
   :outertype: DateUtil

now
^^^

.. java:method:: public static DateTime now()
   :outertype: DateUtil

nowUTC
^^^^^^

.. java:method:: public static DateTime nowUTC()
   :outertype: DateUtil

setTimeZone
^^^^^^^^^^^

.. java:method:: public static DateTime setTimeZone(DateTime dateTime)
   :outertype: DateUtil

setTimeZoneUTC
^^^^^^^^^^^^^^

.. java:method:: public static DateTime setTimeZoneUTC(DateTime dateTime)
   :outertype: DateUtil

time
^^^^

.. java:method:: public static Time time(DateTime dateTime)
   :outertype: DateUtil

today
^^^^^

.. java:method:: public static LocalDate today()
   :outertype: DateUtil

tomorrow
^^^^^^^^

.. java:method:: public static LocalDate tomorrow()
   :outertype: DateUtil

