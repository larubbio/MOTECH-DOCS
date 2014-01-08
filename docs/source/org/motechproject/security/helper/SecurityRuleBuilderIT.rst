.. java:import:: org.junit Rule

.. java:import:: org.junit Test

.. java:import:: org.junit.rules ExpectedException

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.builder SecurityRuleBuilder

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.ex SecurityConfigException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.web SecurityFilterChain

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util Arrays

.. java:import:: java.util HashSet

SecurityRuleBuilderIT
=====================

.. java:package:: org.motechproject.security.helper
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class SecurityRuleBuilderIT

Fields
------
configException
^^^^^^^^^^^^^^^

.. java:field:: @Rule public ExpectedException configException
   :outertype: SecurityRuleBuilderIT

Methods
-------
testMinimalRequirements
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testMinimalRequirements()
   :outertype: SecurityRuleBuilderIT

testShouldRequireMethodsSupported
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldRequireMethodsSupported()
   :outertype: SecurityRuleBuilderIT

testShouldRequirePattern
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldRequirePattern()
   :outertype: SecurityRuleBuilderIT

testShouldRequireProtocol
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldRequireProtocol()
   :outertype: SecurityRuleBuilderIT

testShouldRequireSupportedScheme
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testShouldRequireSupportedScheme()
   :outertype: SecurityRuleBuilderIT

