.. java:import:: java.io IOException

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.security.core AuthenticationException

.. java:import:: org.springframework.security.web.authentication.www BasicAuthenticationEntryPoint

.. java:import:: org.springframework.util Assert

MotechRestBasicAuthenticationEntryPoint
=======================================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechRestBasicAuthenticationEntryPoint extends BasicAuthenticationEntryPoint

   A custom entry point that is invoked when there is an authentication exception within the filter. This ensures that when a user does not have login privileges and are unable to authenticate, a 401 unauthorized response is returned.

Fields
------
SECURITY_REALM_KEY
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SECURITY_REALM_KEY
   :outertype: MotechRestBasicAuthenticationEntryPoint

Constructors
------------
MotechRestBasicAuthenticationEntryPoint
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechRestBasicAuthenticationEntryPoint(SettingsFacade settingsFacade)
   :outertype: MotechRestBasicAuthenticationEntryPoint

Methods
-------
commence
^^^^^^^^

.. java:method:: @Override public void commence(HttpServletRequest request, HttpServletResponse response, AuthenticationException authException) throws IOException
   :outertype: MotechRestBasicAuthenticationEntryPoint

