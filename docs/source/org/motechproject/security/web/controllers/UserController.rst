.. java:import:: org.apache.commons.lang RandomStringUtils

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.motechproject.security.ex EmailExistsException

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.mail MailSendException

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io Writer

.. java:import:: java.util List

UserController
==============

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: @Controller public class UserController

   The \ ``UserController``\  class is responsible for handling web requests, connected with users.

Methods
-------
changeEmail
^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void changeEmail(String userName, String email)
   :outertype: UserController

changePassword
^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void changePassword(String userName, String password)
   :outertype: UserController

currentUser
^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping @ResponseBody public UserDto currentUser()
   :outertype: UserController

deleteUser
^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void deleteUser(UserDto user)
   :outertype: UserController

getUser
^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping @ResponseBody public UserDto getUser(String userName)
   :outertype: UserController

getUsers
^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<MotechUserProfile> getUsers()
   :outertype: UserController

handleEmailExistsException
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler public void handleEmailExistsException(HttpServletResponse response) throws IOException
   :outertype: UserController

handleMailSendException
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler public void handleMailSendException(HttpServletResponse response) throws IOException
   :outertype: UserController

loginMode
^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String loginMode()
   :outertype: UserController

saveUser
^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveUser(UserDto user)
   :outertype: UserController

updateUser
^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void updateUser(UserDto user)
   :outertype: UserController

