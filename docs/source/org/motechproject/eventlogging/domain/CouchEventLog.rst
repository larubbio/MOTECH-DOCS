.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: java.util Map

CouchEventLog
=============

.. java:package:: org.motechproject.eventlogging.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class CouchEventLog extends MotechBaseDataObject

Constructors
------------
CouchEventLog
^^^^^^^^^^^^^

.. java:constructor:: public CouchEventLog()
   :outertype: CouchEventLog

CouchEventLog
^^^^^^^^^^^^^

.. java:constructor:: public CouchEventLog(String subject, Map<String, Object> parameters, DateTime timeStamp)
   :outertype: CouchEventLog

Methods
-------
getParameters
^^^^^^^^^^^^^

.. java:method:: public Map<String, Object> getParameters()
   :outertype: CouchEventLog

getSubject
^^^^^^^^^^

.. java:method:: public String getSubject()
   :outertype: CouchEventLog

getTimeStamp
^^^^^^^^^^^^

.. java:method:: public DateTime getTimeStamp()
   :outertype: CouchEventLog

setParameters
^^^^^^^^^^^^^

.. java:method:: public void setParameters(Map<String, Object> parameters)
   :outertype: CouchEventLog

setSubject
^^^^^^^^^^

.. java:method:: public void setSubject(String subject)
   :outertype: CouchEventLog

setTimeStamp
^^^^^^^^^^^^

.. java:method:: public void setTimeStamp(DateTime timeStamp)
   :outertype: CouchEventLog

