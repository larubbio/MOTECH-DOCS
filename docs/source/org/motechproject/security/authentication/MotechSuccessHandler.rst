.. java:import:: org.motechproject.security.helper SessionHandler

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.web.authentication SavedRequestAwareAuthenticationSuccessHandler

.. java:import:: javax.servlet ServletException

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

MotechSuccessHandler
====================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechSuccessHandler extends SavedRequestAwareAuthenticationSuccessHandler

Methods
-------
onAuthenticationSuccess
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void onAuthenticationSuccess(HttpServletRequest request, HttpServletResponse response, Authentication authentication) throws ServletException, IOException
   :outertype: MotechSuccessHandler

