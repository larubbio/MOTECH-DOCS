.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: org.motechproject.scheduler.domain JobBasicInfo

JobsRecords
===========

.. java:package:: org.motechproject.scheduler.web.domain
   :noindex:

.. java:type:: public class JobsRecords

   JobsRecords is the class which wraps the JobBasicInfo list for view layer.

Constructors
------------
JobsRecords
^^^^^^^^^^^

.. java:constructor:: public JobsRecords(Integer page, Integer rows, List<JobBasicInfo> allRecords)
   :outertype: JobsRecords

Methods
-------
getPage
^^^^^^^

.. java:method:: public Integer getPage()
   :outertype: JobsRecords

getRecords
^^^^^^^^^^

.. java:method:: public Integer getRecords()
   :outertype: JobsRecords

getRows
^^^^^^^

.. java:method:: public List<JobBasicInfo> getRows()
   :outertype: JobsRecords

getTotal
^^^^^^^^

.. java:method:: public Integer getTotal()
   :outertype: JobsRecords

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: JobsRecords

