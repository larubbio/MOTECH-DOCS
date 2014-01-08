.. java:import:: java.util List

EventQueryService
=================

.. java:package:: org.motechproject.eventlogging.service
   :noindex:

.. java:type:: public interface EventQueryService<T>

   Class to query Couch for stored events.

Methods
-------
getAllEventsByParameter
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<T> getAllEventsByParameter(String parameter, String value)
   :outertype: EventQueryService

   Queries the database for all events that match a given parameter and key value pair.

   :param parameter: The parameter from the event.
   :param value: The value the event should have.
   :return: A list of informational objects that match the key value pair.

getAllEventsBySubject
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<T> getAllEventsBySubject(String subject)
   :outertype: EventQueryService

   Queries the database for all events that match a given subject.

   :param subject: The subject of the event.
   :return: A list of informational objects that match the event subject.

getAllEventsBySubjectAndParameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  List<T> getAllEventsBySubjectAndParameter(String subject, String parameter, String value)
   :outertype: EventQueryService

   Queries the database for all events that match a given subject and parameter and key value pair.

   :param subject: The subject of the event.
   :param parameter: The parameter from the event.
   :param value: The value the event should have.
   :return: A list of informational objects that match the subject as well as the key value pair.

