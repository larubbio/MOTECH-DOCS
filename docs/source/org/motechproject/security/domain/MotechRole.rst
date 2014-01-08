.. java:import:: java.util List

MotechRole
==========

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: public interface MotechRole

   Interface that represents Motech user roles.

Methods
-------
getPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method::  List<String> getPermissionNames()
   :outertype: MotechRole

getRoleName
^^^^^^^^^^^

.. java:method::  String getRoleName()
   :outertype: MotechRole

hasPermission
^^^^^^^^^^^^^

.. java:method::  boolean hasPermission(String permissionName)
   :outertype: MotechRole

isDeletable
^^^^^^^^^^^

.. java:method::  boolean isDeletable()
   :outertype: MotechRole

removePermission
^^^^^^^^^^^^^^^^

.. java:method::  void removePermission(String permissionName)
   :outertype: MotechRole

setDeletable
^^^^^^^^^^^^

.. java:method::  void setDeletable(boolean deletable)
   :outertype: MotechRole

setPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method::  void setPermissionNames(List<String> perrmissionNames)
   :outertype: MotechRole

setRoleName
^^^^^^^^^^^

.. java:method::  void setRoleName(String roleName)
   :outertype: MotechRole

