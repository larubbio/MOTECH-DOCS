.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.util List

PermissionController
====================

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: @Controller @PreAuthorize @RequestMapping public class PermissionController

   Controller used for CRUD operations on permission objects.

Methods
-------
deletePermission
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void deletePermission(String permissionName)
   :outertype: PermissionController

getPermissions
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<PermissionDto> getPermissions()
   :outertype: PermissionController

savePermission
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void savePermission(String permissionName)
   :outertype: PermissionController

