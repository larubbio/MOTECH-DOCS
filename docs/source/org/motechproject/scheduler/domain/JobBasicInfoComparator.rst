.. java:import:: org.joda.time.format DateTimeFormat

.. java:import:: org.joda.time DateTime

.. java:import:: org.joda.time.format DateTimeFormatter

.. java:import:: java.util Comparator

JobBasicInfoComparator
======================

.. java:package:: org.motechproject.scheduler.domain
   :noindex:

.. java:type:: public class JobBasicInfoComparator implements Comparator<JobBasicInfo>

   JobBasicInfoComparator is the implementation of Comparator interface, which allows different outcome of compare(..) method. Thanks to this, it is possible to sort JobBasicInfos based on single fields.

Constructors
------------
JobBasicInfoComparator
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public JobBasicInfoComparator(Boolean ascending, String compareField)
   :outertype: JobBasicInfoComparator

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(JobBasicInfo o1, JobBasicInfo o2)
   :outertype: JobBasicInfoComparator

