.. java:import:: org.motechproject.security.ex InvalidTokenException

.. java:import:: org.motechproject.security.ex UserNotFoundException

.. java:import:: org.motechproject.security.password NonAdminUserException

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

PasswordRecoveryService
=======================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface PasswordRecoveryService

Methods
-------
cleanUpExpiredRecoveries
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void cleanUpExpiredRecoveries()
   :outertype: PasswordRecoveryService

oneTimeTokenOpenId
^^^^^^^^^^^^^^^^^^

.. java:method::  void oneTimeTokenOpenId(String email) throws UserNotFoundException, NonAdminUserException
   :outertype: PasswordRecoveryService

passwordRecoveryRequest
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void passwordRecoveryRequest(String email) throws UserNotFoundException
   :outertype: PasswordRecoveryService

resetPassword
^^^^^^^^^^^^^

.. java:method::  void resetPassword(String token, String password, String passwordConfirmation) throws InvalidTokenException
   :outertype: PasswordRecoveryService

validateToken
^^^^^^^^^^^^^

.. java:method::  boolean validateToken(String token)
   :outertype: PasswordRecoveryService

validateTokenAndLoginUser
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void validateTokenAndLoginUser(String token, HttpServletRequest request, HttpServletResponse response) throws IOException
   :outertype: PasswordRecoveryService

