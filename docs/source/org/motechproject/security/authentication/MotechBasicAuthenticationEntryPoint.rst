.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.web.authentication.www BasicAuthenticationEntryPoint

.. java:import:: org.springframework.util Assert

MotechBasicAuthenticationEntryPoint
===================================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechBasicAuthenticationEntryPoint extends BasicAuthenticationEntryPoint

   An entry point for BASIC authentications, sets the correct server realm key.

Fields
------
SECURITY_REALM_KEY
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String SECURITY_REALM_KEY
   :outertype: MotechBasicAuthenticationEntryPoint

Constructors
------------
MotechBasicAuthenticationEntryPoint
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechBasicAuthenticationEntryPoint(SettingsFacade settingsFacade)
   :outertype: MotechBasicAuthenticationEntryPoint

