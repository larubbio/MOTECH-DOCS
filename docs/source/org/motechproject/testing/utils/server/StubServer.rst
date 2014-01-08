.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.mortbay.jetty Request

.. java:import:: org.mortbay.jetty Server

.. java:import:: org.mortbay.jetty.servlet Context

.. java:import:: org.mortbay.jetty.servlet DefaultServlet

.. java:import:: org.mortbay.jetty.servlet ServletHolder

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: javax.servlet ServletException

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.util HashMap

.. java:import:: java.util Map

StubServer
==========

.. java:package:: org.motechproject.testing.utils.server
   :noindex:

.. java:type:: public class StubServer

Fields
------
OK
^^

.. java:field:: public static final String OK
   :outertype: StubServer

Constructors
------------
StubServer
^^^^^^^^^^

.. java:constructor:: public StubServer(int port, String contextPath)
   :outertype: StubServer

Methods
-------
detailForRequest
^^^^^^^^^^^^^^^^

.. java:method:: public RequestInfo detailForRequest(String contextPath)
   :outertype: StubServer

start
^^^^^

.. java:method:: public StubServer start()
   :outertype: StubServer

stop
^^^^

.. java:method:: public void stop()
   :outertype: StubServer

waitingForRequests
^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean waitingForRequests()
   :outertype: StubServer

