.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.helper SessionHandler

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.authentication AbstractAuthenticationToken

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContext

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.security.openid OpenIDAuthenticationToken

.. java:import:: org.springframework.stereotype Service

.. java:import:: javax.servlet.http HttpSession

.. java:import:: java.util Collection

UserContextServiceImpl
======================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class UserContextServiceImpl implements UserContextService

   Implementation class for @UserContextService. APIs to refresh user contexts for users in session

Methods
-------
refreshAllUsersContextIfActive
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void refreshAllUsersContextIfActive()
   :outertype: UserContextServiceImpl

refreshUserContextIfActive
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void refreshUserContextIfActive(String userName)
   :outertype: UserContextServiceImpl

