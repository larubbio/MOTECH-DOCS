.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.service EventLoggingService

.. java:import:: java.util HashSet

.. java:import:: java.util Set

TestEventLoggingService
=======================

.. java:package:: org.motechproject.eventlogging.osgi
   :noindex:

.. java:type:: public class TestEventLoggingService implements EventLoggingService

Methods
-------
getLoggedEventSubjects
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Set<String> getLoggedEventSubjects()
   :outertype: TestEventLoggingService

isLogged
^^^^^^^^

.. java:method:: public boolean isLogged()
   :outertype: TestEventLoggingService

logEvent
^^^^^^^^

.. java:method:: @Override public synchronized void logEvent(MotechEvent event)
   :outertype: TestEventLoggingService

