.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: java.util List

AllMotechPermissions
====================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: public interface AllMotechPermissions

   Interface for the permission repository, used for persisting permission objects.

Methods
-------
add
^^^

.. java:method::  void add(MotechPermission permission)
   :outertype: AllMotechPermissions

delete
^^^^^^

.. java:method::  void delete(MotechPermission permission)
   :outertype: AllMotechPermissions

findByPermissionName
^^^^^^^^^^^^^^^^^^^^

.. java:method::  MotechPermission findByPermissionName(String permissionName)
   :outertype: AllMotechPermissions

getPermissions
^^^^^^^^^^^^^^

.. java:method::  List<MotechPermission> getPermissions()
   :outertype: AllMotechPermissions

