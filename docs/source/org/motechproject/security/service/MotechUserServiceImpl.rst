.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.motechproject.security UserRoleNames

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain MotechUserCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.motechproject.security.email EmailSender

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

.. java:import:: java.util Locale

MotechUserServiceImpl
=====================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class MotechUserServiceImpl implements MotechUserService

   Implementation of MotechUserService. Allows to search and manage users.

Methods
-------
activateUser
^^^^^^^^^^^^

.. java:method:: @Override public void activateUser(String username)
   :outertype: MotechUserServiceImpl

changePassword
^^^^^^^^^^^^^^

.. java:method:: @Override public MotechUserProfile changePassword(String username, String oldPassword, String newPassword)
   :outertype: MotechUserServiceImpl

deleteUser
^^^^^^^^^^

.. java:method:: @Override public void deleteUser(UserDto user)
   :outertype: MotechUserServiceImpl

getCurrentUser
^^^^^^^^^^^^^^

.. java:method:: @Override public UserDto getCurrentUser()
   :outertype: MotechUserServiceImpl

getLocale
^^^^^^^^^

.. java:method:: @Override public Locale getLocale(String userName)
   :outertype: MotechUserServiceImpl

getOpenIdUsers
^^^^^^^^^^^^^^

.. java:method:: @Override public List<MotechUserProfile> getOpenIdUsers()
   :outertype: MotechUserServiceImpl

getRoles
^^^^^^^^

.. java:method:: @Override public List<String> getRoles(String userName)
   :outertype: MotechUserServiceImpl

getUser
^^^^^^^

.. java:method:: @Override public UserDto getUser(String userName)
   :outertype: MotechUserServiceImpl

getUserByEmail
^^^^^^^^^^^^^^

.. java:method:: @Override public UserDto getUserByEmail(String email)
   :outertype: MotechUserServiceImpl

getUsers
^^^^^^^^

.. java:method:: @Override public List<MotechUserProfile> getUsers()
   :outertype: MotechUserServiceImpl

hasActiveAdminUser
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean hasActiveAdminUser()
   :outertype: MotechUserServiceImpl

hasUser
^^^^^^^

.. java:method:: @Override public boolean hasUser(String username)
   :outertype: MotechUserServiceImpl

register
^^^^^^^^

.. java:method:: @Override public void register(String username, String password, String email, String externalId, List<String> roles, Locale locale)
   :outertype: MotechUserServiceImpl

register
^^^^^^^^

.. java:method:: @Override public void register(String username, String password, String email, String externalId, List<String> roles, Locale locale, boolean isActive, String openId)
   :outertype: MotechUserServiceImpl

retrieveUserByCredentials
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public MotechUserProfile retrieveUserByCredentials(String username, String password)
   :outertype: MotechUserServiceImpl

sendLoginInformation
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void sendLoginInformation(String userName, String password)
   :outertype: MotechUserServiceImpl

setLocale
^^^^^^^^^

.. java:method:: @Override public void setLocale(String userName, Locale locale)
   :outertype: MotechUserServiceImpl

updateUserDetailsWithPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateUserDetailsWithPassword(UserDto user)
   :outertype: MotechUserServiceImpl

updateUserDetailsWithoutPassword
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateUserDetailsWithoutPassword(UserDto user)
   :outertype: MotechUserServiceImpl

