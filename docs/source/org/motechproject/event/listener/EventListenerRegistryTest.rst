.. java:import:: junitx.util PrivateAccessor

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Matchers

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.impl EventListenerRegistry

.. java:import:: org.motechproject.event.osgi MetricsServiceManager

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Set

EventListenerRegistryTest
=========================

.. java:package:: org.motechproject.event.listener
   :noindex:

.. java:type:: public class EventListenerRegistryTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: EventListenerRegistryTest

testAddThenRemoveListener
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testAddThenRemoveListener()
   :outertype: EventListenerRegistryTest

testAddingWildCardListenerThenRemoving
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testAddingWildCardListenerThenRemoving()
   :outertype: EventListenerRegistryTest

testEmptyEventListRegistration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testEmptyEventListRegistration() throws NoSuchFieldException
   :outertype: EventListenerRegistryTest

testGetEmptyListenerList
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetEmptyListenerList()
   :outertype: EventListenerRegistryTest

testGetListeners
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetListeners()
   :outertype: EventListenerRegistryTest

testHasListener_No
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testHasListener_No()
   :outertype: EventListenerRegistryTest

testHasListener_NoEmpty
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testHasListener_NoEmpty()
   :outertype: EventListenerRegistryTest

testHasListener_Yes
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testHasListener_Yes()
   :outertype: EventListenerRegistryTest

testHasListener_YesWildcard
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testHasListener_YesWildcard()
   :outertype: EventListenerRegistryTest

testNullEventListenerRegistration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNullEventListenerRegistration()
   :outertype: EventListenerRegistryTest

testNullEventTypeRegistration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNullEventTypeRegistration()
   :outertype: EventListenerRegistryTest

testRegisterForMultipleEvents
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterForMultipleEvents()
   :outertype: EventListenerRegistryTest

testRegisterForSameEventTwice
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterForSameEventTwice()
   :outertype: EventListenerRegistryTest

testRegisterMultipleListener
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterMultipleListener()
   :outertype: EventListenerRegistryTest

testRegisterSingleListener
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterSingleListener()
   :outertype: EventListenerRegistryTest

testRegisterTwice
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRegisterTwice()
   :outertype: EventListenerRegistryTest

testRemovingListenerPreservesOtherListeners
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRemovingListenerPreservesOtherListeners()
   :outertype: EventListenerRegistryTest

