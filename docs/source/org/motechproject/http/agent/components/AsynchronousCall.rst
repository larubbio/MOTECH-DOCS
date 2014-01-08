.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventRelay

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

AsynchronousCall
================

.. java:package:: org.motechproject.http.agent.components
   :noindex:

.. java:type:: @Component public class AsynchronousCall implements CommunicationType

Constructors
------------
AsynchronousCall
^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AsynchronousCall(EventRelay eventRelay)
   :outertype: AsynchronousCall

Methods
-------
send
^^^^

.. java:method:: public void send(MotechEvent motechEvent)
   :outertype: AsynchronousCall

