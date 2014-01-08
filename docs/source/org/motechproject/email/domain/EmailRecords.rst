.. java:import:: java.util ArrayList

.. java:import:: java.util List

EmailRecords
============

.. java:package:: org.motechproject.email.domain
   :noindex:

.. java:type:: public class EmailRecords<T>

   The \ ``EmailRecords``\  class wraps the {@Link EmailRecord} list for view layer and stores current item count.

Constructors
------------
EmailRecords
^^^^^^^^^^^^

.. java:constructor:: public EmailRecords()
   :outertype: EmailRecords

EmailRecords
^^^^^^^^^^^^

.. java:constructor:: public EmailRecords(Integer page, Integer rows, List<T> allRecords)
   :outertype: EmailRecords

Methods
-------
getPage
^^^^^^^

.. java:method:: public Integer getPage()
   :outertype: EmailRecords

getRecords
^^^^^^^^^^

.. java:method:: public Integer getRecords()
   :outertype: EmailRecords

getRows
^^^^^^^

.. java:method:: public List<T> getRows()
   :outertype: EmailRecords

getTotal
^^^^^^^^

.. java:method:: public Integer getTotal()
   :outertype: EmailRecords

setRows
^^^^^^^

.. java:method:: public void setRows(List<T> rows)
   :outertype: EmailRecords

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: EmailRecords

