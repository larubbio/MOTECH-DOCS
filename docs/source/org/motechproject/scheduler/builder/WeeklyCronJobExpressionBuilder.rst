.. java:import:: org.motechproject.commons.date.model DayOfWeek

.. java:import:: org.motechproject.commons.date.model Time

WeeklyCronJobExpressionBuilder
==============================

.. java:package:: org.motechproject.scheduler.builder
   :noindex:

.. java:type:: public class WeeklyCronJobExpressionBuilder

Constructors
------------
WeeklyCronJobExpressionBuilder
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public WeeklyCronJobExpressionBuilder(DayOfWeek dayOfWeek)
   :outertype: WeeklyCronJobExpressionBuilder

WeeklyCronJobExpressionBuilder
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public WeeklyCronJobExpressionBuilder(int dayOfWeekNumber)
   :outertype: WeeklyCronJobExpressionBuilder

Methods
-------
build
^^^^^

.. java:method:: public String build()
   :outertype: WeeklyCronJobExpressionBuilder

withTime
^^^^^^^^

.. java:method:: public WeeklyCronJobExpressionBuilder withTime(Time time)
   :outertype: WeeklyCronJobExpressionBuilder

