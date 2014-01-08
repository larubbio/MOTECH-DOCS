EventLoggingServiceManager
==========================

.. java:package:: org.motechproject.eventlogging.service
   :noindex:

.. java:type:: public interface EventLoggingServiceManager

   A logging service manager that allows for register logging services. This class is exposed as an OSGi service to support cross bundle registration.

Methods
-------
registerEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void registerEventLoggingService(EventLoggingService eventLoggingService)
   :outertype: EventLoggingServiceManager

   Register a logging service in the platform, which will generate listeners for that logging service based on the subjects it listens on.

   :param eventLoggingService: The logging service to add to the platform.

updateEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updateEventLoggingService(EventLoggingService eventLoggingService)
   :outertype: EventLoggingServiceManager

   Not yet implemented

   :param eventLoggingService:

