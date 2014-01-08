.. java:import:: org.motechproject.eventlogging.domain CouchEventLog

.. java:import:: org.motechproject.eventlogging.repository AllCouchLogs

.. java:import:: org.motechproject.eventlogging.service EventQueryService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

CouchEventQueryService
======================

.. java:package:: org.motechproject.eventlogging.service.impl
   :noindex:

.. java:type:: @Service public class CouchEventQueryService implements EventQueryService<CouchEventLog>

Methods
-------
getAllEventsByParameter
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<CouchEventLog> getAllEventsByParameter(String parameter, String value)
   :outertype: CouchEventQueryService

getAllEventsBySubject
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<CouchEventLog> getAllEventsBySubject(String subject)
   :outertype: CouchEventQueryService

getAllEventsBySubjectAndParameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<CouchEventLog> getAllEventsBySubjectAndParameter(String subject, String parameter, String value)
   :outertype: CouchEventQueryService

