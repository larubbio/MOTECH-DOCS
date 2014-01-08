.. java:import:: org.motechproject.mds.web.domain FieldRecord

.. java:import:: org.motechproject.mds.web.domain HistoryRecord

.. java:import:: java.text DateFormat

.. java:import:: java.text ParseException

.. java:import:: java.text SimpleDateFormat

.. java:import:: java.util Comparator

.. java:import:: java.util Date

.. java:import:: java.util Locale

HistoryRecordComparator
=======================

.. java:package:: org.motechproject.mds.web.comparator
   :noindex:

.. java:type:: public class HistoryRecordComparator implements Comparator<HistoryRecord>

   The \ ``HistoryRecordComparator``\  class compares two objects of \ :java:ref:`HistoryRecord`\  by value of their field property.

Constructors
------------
HistoryRecordComparator
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public HistoryRecordComparator(boolean sortAscending, String compareField)
   :outertype: HistoryRecordComparator

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(HistoryRecord one, HistoryRecord two)
   :outertype: HistoryRecordComparator

