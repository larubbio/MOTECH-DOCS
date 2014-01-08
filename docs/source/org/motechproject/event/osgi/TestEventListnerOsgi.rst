.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: java.util ArrayList

.. java:import:: java.util List

TestEventListnerOsgi
====================

.. java:package:: org.motechproject.event.osgi
   :noindex:

.. java:type:: public class TestEventListnerOsgi

Fields
------
TEST_SUBJECT_OSGI
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String TEST_SUBJECT_OSGI
   :outertype: TestEventListnerOsgi

Methods
-------
getReceivedEvents
^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getReceivedEvents()
   :outertype: TestEventListnerOsgi

testSubjectOsgiHandler
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @MotechListener public synchronized void testSubjectOsgiHandler(MotechEvent event)
   :outertype: TestEventListnerOsgi

