.. java:import:: org.joda.time DateTime

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: org.motechproject.testing.utils BaseUnitTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util List

.. java:import:: java.util Locale

AllPasswordRecoveriesIT
=======================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllPasswordRecoveriesIT extends BaseUnitTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: AllPasswordRecoveriesIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: AllPasswordRecoveriesIT

testFindForToken
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testFindForToken()
   :outertype: AllPasswordRecoveriesIT

testFindForUser
^^^^^^^^^^^^^^^

.. java:method:: @Test public void testFindForUser()
   :outertype: AllPasswordRecoveriesIT

testGetExpired
^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetExpired()
   :outertype: AllPasswordRecoveriesIT

testRemoveOldRecovery
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testRemoveOldRecovery()
   :outertype: AllPasswordRecoveriesIT

