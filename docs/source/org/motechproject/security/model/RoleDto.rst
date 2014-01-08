.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Objects

RoleDto
=======

.. java:package:: org.motechproject.security.model
   :noindex:

.. java:type:: public class RoleDto

   Transfer Motech role data between representations. Role data transfer object facilitates exchange of role data among services, repository, and client user interface.

Constructors
------------
RoleDto
^^^^^^^

.. java:constructor:: public RoleDto()
   :outertype: RoleDto

RoleDto
^^^^^^^

.. java:constructor:: public RoleDto(MotechRole motechRole)
   :outertype: RoleDto

RoleDto
^^^^^^^

.. java:constructor:: public RoleDto(String roleName, List<String> permissionNames)
   :outertype: RoleDto

RoleDto
^^^^^^^

.. java:constructor:: public RoleDto(String roleName, List<String> permissionNames, boolean deletable)
   :outertype: RoleDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: RoleDto

getOriginalRoleName
^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getOriginalRoleName()
   :outertype: RoleDto

getPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getPermissionNames()
   :outertype: RoleDto

getRoleName
^^^^^^^^^^^

.. java:method:: public String getRoleName()
   :outertype: RoleDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: RoleDto

isDeletable
^^^^^^^^^^^

.. java:method:: public boolean isDeletable()
   :outertype: RoleDto

setDeletable
^^^^^^^^^^^^

.. java:method:: public void setDeletable(boolean deletable)
   :outertype: RoleDto

setOriginalRoleName
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setOriginalRoleName(String originalRoleName)
   :outertype: RoleDto

setPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method:: public void setPermissionNames(List<String> permissionNames)
   :outertype: RoleDto

setRoleName
^^^^^^^^^^^

.. java:method:: public void setRoleName(String roleName)
   :outertype: RoleDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: RoleDto

