.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeZone

.. java:import:: org.joda.time LocalDate

.. java:import:: java.util Calendar

.. java:import:: java.util TimeZone

DefaultDateTimeSource
=====================

.. java:package:: org.motechproject.commons.date.util.datetime
   :noindex:

.. java:type:: public class DefaultDateTimeSource implements DateTimeSource

Constructors
------------
DefaultDateTimeSource
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public DefaultDateTimeSource()
   :outertype: DefaultDateTimeSource

Methods
-------
now
^^^

.. java:method:: @Override public DateTime now()
   :outertype: DefaultDateTimeSource

timeZone
^^^^^^^^

.. java:method:: @Override public DateTimeZone timeZone()
   :outertype: DefaultDateTimeSource

today
^^^^^

.. java:method:: @Override public LocalDate today()
   :outertype: DefaultDateTimeSource

