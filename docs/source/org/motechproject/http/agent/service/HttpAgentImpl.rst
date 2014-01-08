.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.http.agent.components AsynchronousCall

.. java:import:: org.motechproject.http.agent.components SynchronousCall

.. java:import:: org.motechproject.http.agent.domain EventDataKeys

.. java:import:: org.motechproject.http.agent.domain EventSubjects

.. java:import:: org.motechproject.http.agent.domain Method

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util HashMap

.. java:import:: java.util Map

HttpAgentImpl
=============

.. java:package:: org.motechproject.http.agent.service
   :noindex:

.. java:type:: @Service public class HttpAgentImpl implements HttpAgent

Constructors
------------
HttpAgentImpl
^^^^^^^^^^^^^

.. java:constructor:: @Autowired public HttpAgentImpl(AsynchronousCall asynchronousCall, SynchronousCall synchronousCall)
   :outertype: HttpAgentImpl

Methods
-------
execute
^^^^^^^

.. java:method:: @Override public void execute(String url, Object data, Method method)
   :outertype: HttpAgentImpl

executeSync
^^^^^^^^^^^

.. java:method:: @Override public void executeSync(String url, Object data, Method method)
   :outertype: HttpAgentImpl

