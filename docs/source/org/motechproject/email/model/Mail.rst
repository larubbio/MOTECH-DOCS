.. java:import:: org.codehaus.jackson.map.annotate JsonDeserialize

.. java:import:: org.motechproject.email.json MailDeserializer

.. java:import:: java.util Objects

Mail
====

.. java:package:: org.motechproject.email.model
   :noindex:

.. java:type:: @JsonDeserialize public class Mail

Constructors
------------
Mail
^^^^

.. java:constructor:: public Mail(String fromAddress, String toAddress, String subject, String message)
   :outertype: Mail

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: Mail

getFromAddress
^^^^^^^^^^^^^^

.. java:method:: public String getFromAddress()
   :outertype: Mail

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: Mail

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: Mail

getText
^^^^^^^

.. java:method:: @Deprecated public String getText()
   :outertype: Mail

getToAddress
^^^^^^^^^^^^

.. java:method:: public String getToAddress()
   :outertype: Mail

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: Mail

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: Mail

