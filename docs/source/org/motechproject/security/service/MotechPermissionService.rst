.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: java.util List

MotechPermissionService
=======================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface MotechPermissionService

   Service for managing Motech permissions.

Methods
-------
addPermission
^^^^^^^^^^^^^

.. java:method::  void addPermission(PermissionDto permission)
   :outertype: MotechPermissionService

deletePermission
^^^^^^^^^^^^^^^^

.. java:method::  void deletePermission(String permissionName)
   :outertype: MotechPermissionService

getPermissions
^^^^^^^^^^^^^^

.. java:method::  List<PermissionDto> getPermissions()
   :outertype: MotechPermissionService

