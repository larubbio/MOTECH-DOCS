.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeZone

.. java:import:: org.joda.time LocalDate

.. java:import:: org.joda.time LocalTime

.. java:import:: org.motechproject.commons.date.util.datetime DateTimeSource

MockDateTimeSource
==================

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: public class MockDateTimeSource implements DateTimeSource

Constructors
------------
MockDateTimeSource
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MockDateTimeSource(LocalDate localDate)
   :outertype: MockDateTimeSource

MockDateTimeSource
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MockDateTimeSource(DateTime dateTime)
   :outertype: MockDateTimeSource

Methods
-------
now
^^^

.. java:method:: @Override public DateTime now()
   :outertype: MockDateTimeSource

timeZone
^^^^^^^^

.. java:method:: @Override public DateTimeZone timeZone()
   :outertype: MockDateTimeSource

today
^^^^^

.. java:method:: @Override public LocalDate today()
   :outertype: MockDateTimeSource

