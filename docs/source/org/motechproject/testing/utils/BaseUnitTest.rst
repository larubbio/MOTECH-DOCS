.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time LocalDate

.. java:import:: org.joda.time LocalTime

.. java:import:: org.junit After

.. java:import:: org.motechproject.commons.date.util DateTimeSourceUtil

.. java:import:: org.motechproject.commons.date.util.datetime DateTimeSource

.. java:import:: org.motechproject.commons.date.util.datetime DefaultDateTimeSource

.. java:import:: java.text ParseException

.. java:import:: java.text SimpleDateFormat

.. java:import:: java.util Date

BaseUnitTest
============

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: public class BaseUnitTest

Fields
------
DATE_TIME_SOURCE
^^^^^^^^^^^^^^^^

.. java:field:: static final DateTimeSource DATE_TIME_SOURCE
   :outertype: BaseUnitTest

Methods
-------
date
^^^^

.. java:method:: protected DateTime date(int year, int monthOfYear, int dayOfMonth)
   :outertype: BaseUnitTest

date
^^^^

.. java:method:: protected Date date(String date)
   :outertype: BaseUnitTest

dateTime
^^^^^^^^

.. java:method:: protected DateTime dateTime(int year, int monthOfYear, int dayOfMonth, LocalTime localTime)
   :outertype: BaseUnitTest

dateTime
^^^^^^^^

.. java:method:: protected DateTime dateTime(LocalDate localDate, LocalTime localTime)
   :outertype: BaseUnitTest

mockCurrentDate
^^^^^^^^^^^^^^^

.. java:method:: protected void mockCurrentDate(DateTime currentDateTime)
   :outertype: BaseUnitTest

mockCurrentDate
^^^^^^^^^^^^^^^

.. java:method:: protected void mockCurrentDate(LocalDate currentDate)
   :outertype: BaseUnitTest

resetDateTimeSource
^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void resetDateTimeSource()
   :outertype: BaseUnitTest

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: BaseUnitTest

