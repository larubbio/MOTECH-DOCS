.. java:import:: java.util Comparator

EmailRecordComparator
=====================

.. java:package:: org.motechproject.email.domain
   :noindex:

.. java:type:: public class EmailRecordComparator implements Comparator<EmailRecord>

   The \ ``EmailRecordComparator``\  class is an implementation of Comparator interface, that allows to compare {@Link EmailRecord} by a single field.

Constructors
------------
EmailRecordComparator
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EmailRecordComparator(Boolean ascending, String compareField)
   :outertype: EmailRecordComparator

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(EmailRecord o1, EmailRecord o2)
   :outertype: EmailRecordComparator

