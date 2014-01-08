.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.motechproject.event.listener.annotations MotechListenerEventProxy

.. java:import:: org.motechproject.eventlogging.service EventLoggingService

.. java:import:: org.motechproject.eventlogging.service EventLoggingServiceManager

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.annotation PostConstruct

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Set

EventLoggingServiceManagerImpl
==============================

.. java:package:: org.motechproject.eventlogging.service.impl
   :noindex:

.. java:type:: @Component public class EventLoggingServiceManagerImpl implements EventLoggingServiceManager

Methods
-------
registerDefaultService
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @PostConstruct public void registerDefaultService()
   :outertype: EventLoggingServiceManagerImpl

registerEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void registerEventLoggingService(EventLoggingService eventLoggingService)
   :outertype: EventLoggingServiceManagerImpl

updateEventLoggingService
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateEventLoggingService(EventLoggingService eventLoggingService)
   :outertype: EventLoggingServiceManagerImpl

