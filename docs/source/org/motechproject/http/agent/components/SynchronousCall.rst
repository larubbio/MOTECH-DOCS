.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.http.agent.listener HttpClientEventListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Component

SynchronousCall
===============

.. java:package:: org.motechproject.http.agent.components
   :noindex:

.. java:type:: @Component public class SynchronousCall implements CommunicationType

Constructors
------------
SynchronousCall
^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public SynchronousCall(HttpClientEventListener httpClientEventListener)
   :outertype: SynchronousCall

Methods
-------
send
^^^^

.. java:method:: @Override public void send(MotechEvent motechEvent)
   :outertype: SynchronousCall

