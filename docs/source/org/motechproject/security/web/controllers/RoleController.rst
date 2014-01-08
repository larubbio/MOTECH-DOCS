.. java:import:: org.motechproject.security.ex RoleHasUserException

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.service MotechRoleService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.security.access.prepost PreAuthorize

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

RoleController
==============

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: @Controller @PreAuthorize @RequestMapping public class RoleController

   Handle HTTP requests from web clients for Manage Roles user interface.

Methods
-------
deleteRole
^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void deleteRole(RoleDto role)
   :outertype: RoleController

getRoles
^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<RoleDto> getRoles()
   :outertype: RoleController

handleRoleHasUserException
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler public void handleRoleHasUserException(HttpServletResponse response) throws IOException
   :outertype: RoleController

role
^^^^

.. java:method:: @ResponseStatus @RequestMapping @ResponseBody public RoleDto role(String roleName)
   :outertype: RoleController

saveRole
^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveRole(RoleDto role)
   :outertype: RoleController

updateRole
^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void updateRole(RoleDto role)
   :outertype: RoleController

