.. java:import:: org.junit Test

.. java:import:: org.motechproject.event.aggregation.model.event AggregatedEventRecord

.. java:import:: java.util HashMap

RuleAgentTest
=============

.. java:package:: org.motechproject.event.aggregation.rule
   :noindex:

.. java:type:: public class RuleAgentTest

Fields
------
ruleAgent
^^^^^^^^^

.. java:field::  RuleAgent ruleAgent
   :outertype: RuleAgentTest

Methods
-------
shouldBeFalseIfFirstEventWasReceivedLessThan10MinutesAgo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBeFalseIfFirstEventWasReceivedLessThan10MinutesAgo()
   :outertype: RuleAgentTest

shouldBeFalseIfSomeEventWasReceivedInTheLast10Minutes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBeFalseIfSomeEventWasReceivedInTheLast10Minutes()
   :outertype: RuleAgentTest

shouldBeTrueIfFirstEventWasReceivedMoreThan10MinutesAgo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBeTrueIfFirstEventWasReceivedMoreThan10MinutesAgo()
   :outertype: RuleAgentTest

shouldBeTrueIfNoEventWasReceivedInTheLast10Minutes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBeTrueIfNoEventWasReceivedInTheLast10Minutes()
   :outertype: RuleAgentTest

