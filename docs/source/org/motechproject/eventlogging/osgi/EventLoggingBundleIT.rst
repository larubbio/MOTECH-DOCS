.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.motechproject.eventlogging.service EventLoggingServiceManager

.. java:import:: org.motechproject.testing.osgi BaseOsgiIT

.. java:import:: org.osgi.framework ServiceReference

EventLoggingBundleIT
====================

.. java:package:: org.motechproject.eventlogging.osgi
   :noindex:

.. java:type:: public class EventLoggingBundleIT extends BaseOsgiIT

Fields
------
TEST_EVENT_SUBJECT
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String TEST_EVENT_SUBJECT
   :outertype: EventLoggingBundleIT

Methods
-------
testEventLoggingServiceManager
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void testEventLoggingServiceManager() throws InterruptedException
   :outertype: EventLoggingBundleIT

