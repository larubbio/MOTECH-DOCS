.. java:import:: org.apache.commons.lang RandomStringUtils

.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.commons.date.util DateTimeSourceUtil

.. java:import:: org.motechproject.commons.date.util DateUtil

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: org.motechproject.security.email EmailSender

.. java:import:: org.motechproject.security.ex InvalidTokenException

.. java:import:: org.motechproject.security.ex UserNotFoundException

.. java:import:: org.motechproject.security.password NonAdminUserException

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.repository AllPasswordRecoveries

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.security.openid OpenIDAttribute

.. java:import:: org.springframework.security.openid OpenIDAuthenticationProvider

.. java:import:: org.springframework.security.openid OpenIDAuthenticationStatus

.. java:import:: org.springframework.security.openid OpenIDAuthenticationToken

.. java:import:: org.springframework.security.web DefaultRedirectStrategy

.. java:import:: org.springframework.security.web RedirectStrategy

.. java:import:: org.springframework.security.web.context HttpSessionSecurityContextRepository

.. java:import:: org.springframework.stereotype Service

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

PasswordRecoveryServiceImpl
===========================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class PasswordRecoveryServiceImpl implements PasswordRecoveryService

Methods
-------
cleanUpExpiredRecoveries
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void cleanUpExpiredRecoveries()
   :outertype: PasswordRecoveryServiceImpl

oneTimeTokenOpenId
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void oneTimeTokenOpenId(String email) throws UserNotFoundException, NonAdminUserException
   :outertype: PasswordRecoveryServiceImpl

passwordRecoveryRequest
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void passwordRecoveryRequest(String email) throws UserNotFoundException
   :outertype: PasswordRecoveryServiceImpl

resetPassword
^^^^^^^^^^^^^

.. java:method:: @Override public void resetPassword(String token, String password, String passwordConfirmation) throws InvalidTokenException
   :outertype: PasswordRecoveryServiceImpl

validateToken
^^^^^^^^^^^^^

.. java:method:: @Override public boolean validateToken(String token)
   :outertype: PasswordRecoveryServiceImpl

validateTokenAndLoginUser
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void validateTokenAndLoginUser(String token, HttpServletRequest request, HttpServletResponse response) throws IOException
   :outertype: PasswordRecoveryServiceImpl

