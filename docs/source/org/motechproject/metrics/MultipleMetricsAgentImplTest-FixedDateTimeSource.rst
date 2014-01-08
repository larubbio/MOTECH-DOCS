.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time DateTimeZone

.. java:import:: org.joda.time LocalDate

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.motechproject.commons.date.util DateTimeSourceUtil

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.commons.date.util.datetime DateTimeSource

.. java:import:: org.motechproject.metrics.impl MultipleMetricsAgentImpl

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

MultipleMetricsAgentImplTest.FixedDateTimeSource
================================================

.. java:package:: org.motechproject.metrics
   :noindex:

.. java:type::  class FixedDateTimeSource implements DateTimeSource
   :outertype: MultipleMetricsAgentImplTest

Constructors
------------
FixedDateTimeSource
^^^^^^^^^^^^^^^^^^^

.. java:constructor::  FixedDateTimeSource(DateTime dateTime)
   :outertype: MultipleMetricsAgentImplTest.FixedDateTimeSource

Methods
-------
now
^^^

.. java:method:: @Override public DateTime now()
   :outertype: MultipleMetricsAgentImplTest.FixedDateTimeSource

timeZone
^^^^^^^^

.. java:method:: @Override public DateTimeZone timeZone()
   :outertype: MultipleMetricsAgentImplTest.FixedDateTimeSource

today
^^^^^

.. java:method:: @Override public LocalDate today()
   :outertype: MultipleMetricsAgentImplTest.FixedDateTimeSource

