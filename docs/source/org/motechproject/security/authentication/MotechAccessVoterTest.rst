.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Locale

.. java:import:: org.junit Test

.. java:import:: org.motechproject.security.domain MotechUserCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.springframework.security.access ConfigAttribute

.. java:import:: org.springframework.security.access SecurityConfig

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

MotechAccessVoterTest
=====================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechAccessVoterTest

Methods
-------
shouldAbstrainIfNoAccessAttributes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void shouldAbstrainIfNoAccessAttributes()
   :outertype: MotechAccessVoterTest

shouldVoteAffirmativeIfUserHasAccess
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldVoteAffirmativeIfUserHasAccess()
   :outertype: MotechAccessVoterTest

shouldVoteNegativeIfUserDoesNotHaveAccess
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void shouldVoteNegativeIfUserDoesNotHaveAccess()
   :outertype: MotechAccessVoterTest

testConfigAttSupport
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testConfigAttSupport()
   :outertype: MotechAccessVoterTest

