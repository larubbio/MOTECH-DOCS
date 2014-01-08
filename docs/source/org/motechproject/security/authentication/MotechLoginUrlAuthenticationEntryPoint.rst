.. java:import:: org.springframework.security.core AuthenticationException

.. java:import:: org.springframework.security.web.authentication LoginUrlAuthenticationEntryPoint

.. java:import:: javax.servlet ServletException

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

MotechLoginUrlAuthenticationEntryPoint
======================================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechLoginUrlAuthenticationEntryPoint extends LoginUrlAuthenticationEntryPoint

Methods
-------
commence
^^^^^^^^

.. java:method:: @Override public void commence(HttpServletRequest request, HttpServletResponse response, AuthenticationException authException) throws IOException, ServletException
   :outertype: MotechLoginUrlAuthenticationEntryPoint

