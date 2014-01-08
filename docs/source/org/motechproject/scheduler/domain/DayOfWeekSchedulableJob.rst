.. java:import:: org.joda.time LocalDate

.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util List

DayOfWeekSchedulableJob
=======================

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public final class DayOfWeekSchedulableJob implements Serializable

   Job that is scheduled on particular days of week

Constructors
------------
DayOfWeekSchedulableJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public DayOfWeekSchedulableJob(MotechEvent motechEvent, LocalDate start, LocalDate end, List<DayOfWeek> days, Time time, boolean ignorePastFiresAtStart)
   :outertype: DayOfWeekSchedulableJob

DayOfWeekSchedulableJob
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public DayOfWeekSchedulableJob(MotechEvent motechEvent, LocalDate start, LocalDate end, List<DayOfWeek> days, Time time)
   :outertype: DayOfWeekSchedulableJob

Methods
-------
getCronDays
^^^^^^^^^^^

.. java:method:: public List<Integer> getCronDays()
   :outertype: DayOfWeekSchedulableJob

getEndDate
^^^^^^^^^^

.. java:method:: public LocalDate getEndDate()
   :outertype: DayOfWeekSchedulableJob

getMotechEvent
^^^^^^^^^^^^^^

.. java:method:: public MotechEvent getMotechEvent()
   :outertype: DayOfWeekSchedulableJob

getStartDate
^^^^^^^^^^^^

.. java:method:: public LocalDate getStartDate()
   :outertype: DayOfWeekSchedulableJob

getTime
^^^^^^^

.. java:method:: public Time getTime()
   :outertype: DayOfWeekSchedulableJob

isIgnorePastFiresAtStart
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean isIgnorePastFiresAtStart()
   :outertype: DayOfWeekSchedulableJob

