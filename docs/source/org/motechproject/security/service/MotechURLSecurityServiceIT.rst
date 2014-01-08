.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Locale

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechRolesCouchdbImpl

.. java:import:: org.motechproject.security.repository AllMotechSecurityRules

.. java:import:: org.motechproject.security.repository AllMotechSecurityRulesCouchdbImpl

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.repository AllMotechUsersCouchdbImpl

.. java:import:: org.motechproject.testing.utils SpringIntegrationTest

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.security.access AccessDeniedException

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContext

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

MotechURLSecurityServiceIT
==========================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class MotechURLSecurityServiceIT extends SpringIntegrationTest

Methods
-------
getDBConnector
^^^^^^^^^^^^^^

.. java:method:: @Override public CouchDbConnector getDBConnector()
   :outertype: MotechURLSecurityServiceIT

onStartUp
^^^^^^^^^

.. java:method:: @Before public void onStartUp()
   :outertype: MotechURLSecurityServiceIT

tearDown
^^^^^^^^

.. java:method:: @After public void tearDown()
   :outertype: MotechURLSecurityServiceIT

testHasReadAccess
^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testHasReadAccess()
   :outertype: MotechURLSecurityServiceIT

testNoReadAccess
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testNoReadAccess()
   :outertype: MotechURLSecurityServiceIT

testUpdateSecurity
^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testUpdateSecurity()
   :outertype: MotechURLSecurityServiceIT

