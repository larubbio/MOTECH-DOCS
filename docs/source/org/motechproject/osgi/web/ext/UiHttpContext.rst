.. java:import:: org.osgi.service.http HttpContext

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.net URL

UiHttpContext
=============

.. java:package:: org.motechproject.osgi.web.ext
   :noindex:

.. java:type:: public class UiHttpContext implements HttpContext

Constructors
------------
UiHttpContext
^^^^^^^^^^^^^

.. java:constructor:: public UiHttpContext(HttpContext context)
   :outertype: UiHttpContext

Methods
-------
getContext
^^^^^^^^^^

.. java:method:: protected HttpContext getContext()
   :outertype: UiHttpContext

getMimeType
^^^^^^^^^^^

.. java:method:: @Override public String getMimeType(String name)
   :outertype: UiHttpContext

getResource
^^^^^^^^^^^

.. java:method:: @Override public URL getResource(String name)
   :outertype: UiHttpContext

handleSecurity
^^^^^^^^^^^^^^

.. java:method:: @Override public boolean handleSecurity(HttpServletRequest request, HttpServletResponse response) throws IOException
   :outertype: UiHttpContext

