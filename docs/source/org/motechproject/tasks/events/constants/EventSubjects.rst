EventSubjects
=============

.. java:package:: org.motechproject.tasks.events.constants
   :noindex:

.. java:type:: public final class EventSubjects

   Utility class containing various event subject values used throughout the tasks module

Fields
------
BASE_SUBJECT
^^^^^^^^^^^^

.. java:field:: public static final String BASE_SUBJECT
   :outertype: EventSubjects

CHANNEL_DEREGISTER_SUBJECT
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String CHANNEL_DEREGISTER_SUBJECT
   :outertype: EventSubjects

CHANNEL_REGISTER_SUBJECT
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String CHANNEL_REGISTER_SUBJECT
   :outertype: EventSubjects

CHANNEL_SUBJECT
^^^^^^^^^^^^^^^

.. java:field:: public static final String CHANNEL_SUBJECT
   :outertype: EventSubjects

CHANNEL_UPDATE_SUBJECT
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String CHANNEL_UPDATE_SUBJECT
   :outertype: EventSubjects

DATA_PROVIDER_SUBJECT
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DATA_PROVIDER_SUBJECT
   :outertype: EventSubjects

DATA_PROVIDER_UPDATE_SUBJECT
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DATA_PROVIDER_UPDATE_SUBJECT
   :outertype: EventSubjects

Methods
-------
createHandlerFailureSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static String createHandlerFailureSubject(String taskName, TaskFailureCause cause)
   :outertype: EventSubjects

createHandlerSuccessSubject
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public static String createHandlerSuccessSubject(String taskName)
   :outertype: EventSubjects

