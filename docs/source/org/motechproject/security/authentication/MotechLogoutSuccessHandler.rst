.. java:import:: org.motechproject.security.helper SessionHandler

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.web.authentication.logout LogoutHandler

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

MotechLogoutSuccessHandler
==========================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: @Component public class MotechLogoutSuccessHandler implements LogoutHandler

   A logout handler for removing Motech user sessions from Motech's internally kept session handler. This is invoked when a user logs out.

Methods
-------
logout
^^^^^^

.. java:method:: @Override public void logout(HttpServletRequest request, HttpServletResponse response, Authentication authentication)
   :outertype: MotechLogoutSuccessHandler

