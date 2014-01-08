.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: java.util List

.. java:import:: java.util Locale

MotechUserService
=================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface MotechUserService

   Service interface that defines APIs to retrieve and manage user details

Methods
-------
activateUser
^^^^^^^^^^^^

.. java:method:: @PreAuthorize  void activateUser(String username)
   :outertype: MotechUserService

changePassword
^^^^^^^^^^^^^^

.. java:method::  MotechUserProfile changePassword(String username, String oldPassword, String newPassword)
   :outertype: MotechUserService

deleteUser
^^^^^^^^^^

.. java:method:: @PreAuthorize  void deleteUser(UserDto user)
   :outertype: MotechUserService

getCurrentUser
^^^^^^^^^^^^^^

.. java:method::  UserDto getCurrentUser()
   :outertype: MotechUserService

getLocale
^^^^^^^^^

.. java:method::  Locale getLocale(String userName)
   :outertype: MotechUserService

getOpenIdUsers
^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  List<MotechUserProfile> getOpenIdUsers()
   :outertype: MotechUserService

getRoles
^^^^^^^^

.. java:method::  List<String> getRoles(String userName)
   :outertype: MotechUserService

getUser
^^^^^^^

.. java:method:: @PreAuthorize  UserDto getUser(String userName)
   :outertype: MotechUserService

getUserByEmail
^^^^^^^^^^^^^^

.. java:method::  UserDto getUserByEmail(String email)
   :outertype: MotechUserService

getUsers
^^^^^^^^

.. java:method:: @PreAuthorize  List<MotechUserProfile> getUsers()
   :outertype: MotechUserService

hasActiveAdminUser
^^^^^^^^^^^^^^^^^^

.. java:method::  boolean hasActiveAdminUser()
   :outertype: MotechUserService

hasUser
^^^^^^^

.. java:method::  boolean hasUser(String username)
   :outertype: MotechUserService

register
^^^^^^^^

.. java:method::  void register(String username, String password, String email, String externalId, List<String> roles, Locale locale)
   :outertype: MotechUserService

register
^^^^^^^^

.. java:method:: @PreAuthorize  void register(String username, String password, String email, String externalId, List<String> roles, Locale locale, boolean isActive, String openId)
   :outertype: MotechUserService

retrieveUserByCredentials
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  MotechUserProfile retrieveUserByCredentials(String username, String password)
   :outertype: MotechUserService

sendLoginInformation
^^^^^^^^^^^^^^^^^^^^

.. java:method::  void sendLoginInformation(String userName, String password)
   :outertype: MotechUserService

setLocale
^^^^^^^^^

.. java:method::  void setLocale(String userName, Locale locale)
   :outertype: MotechUserService

updateUserDetailsWithPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updateUserDetailsWithPassword(UserDto user)
   :outertype: MotechUserService

updateUserDetailsWithoutPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  void updateUserDetailsWithoutPassword(UserDto user)
   :outertype: MotechUserService

