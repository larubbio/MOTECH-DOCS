.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time LocalDate

.. java:import:: org.motechproject.commons.date.util DateTimeSourceUtil

.. java:import:: org.motechproject.commons.date.util.datetime DefaultDateTimeSource

TimeFaker
=========

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: public final class TimeFaker

Methods
-------
fakeNow
^^^^^^^

.. java:method:: public static void fakeNow(DateTime now)
   :outertype: TimeFaker

fakeToday
^^^^^^^^^

.. java:method:: public static void fakeToday(LocalDate today)
   :outertype: TimeFaker

stopFakingTime
^^^^^^^^^^^^^^

.. java:method:: public static void stopFakingTime()
   :outertype: TimeFaker

