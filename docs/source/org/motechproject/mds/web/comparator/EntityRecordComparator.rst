.. java:import:: org.motechproject.mds.web.domain EntityRecord

.. java:import:: org.motechproject.mds.web.domain FieldRecord

.. java:import:: java.util Comparator

EntityRecordComparator
======================

.. java:package:: org.motechproject.mds.web.comparator
   :noindex:

.. java:type:: public class EntityRecordComparator implements Comparator<EntityRecord>

   The \ ``EntityRecordComparator``\  class compares two objects of \ :java:ref:`EntityRecord`\  by value of their field property

Constructors
------------
EntityRecordComparator
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EntityRecordComparator(boolean sortAscending, String compareField)
   :outertype: EntityRecordComparator

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(EntityRecord one, EntityRecord two)
   :outertype: EntityRecordComparator

