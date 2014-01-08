.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: java.util List

MotechRoleService
=================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface MotechRoleService

Methods
-------
createRole
^^^^^^^^^^

.. java:method::  void createRole(RoleDto role)
   :outertype: MotechRoleService

deleteRole
^^^^^^^^^^

.. java:method::  void deleteRole(RoleDto role)
   :outertype: MotechRoleService

getRole
^^^^^^^

.. java:method::  RoleDto getRole(String roleName)
   :outertype: MotechRoleService

getRoles
^^^^^^^^

.. java:method::  List<RoleDto> getRoles()
   :outertype: MotechRoleService

updateRole
^^^^^^^^^^

.. java:method::  void updateRole(RoleDto role)
   :outertype: MotechRoleService

