.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: java.io Serializable

.. java:import:: java.util Objects

PermissionDto
=============

.. java:package:: org.motechproject.security.model
   :noindex:

.. java:type:: public class PermissionDto implements Serializable

   The \ ``PermissionDto``\  contains information about permission.

Constructors
------------
PermissionDto
^^^^^^^^^^^^^

.. java:constructor:: public PermissionDto()
   :outertype: PermissionDto

PermissionDto
^^^^^^^^^^^^^

.. java:constructor:: public PermissionDto(MotechPermission motechPermission)
   :outertype: PermissionDto

PermissionDto
^^^^^^^^^^^^^

.. java:constructor:: public PermissionDto(String permissionName, String bundleName)
   :outertype: PermissionDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: PermissionDto

getBundleName
^^^^^^^^^^^^^

.. java:method:: public String getBundleName()
   :outertype: PermissionDto

getPermissionName
^^^^^^^^^^^^^^^^^

.. java:method:: public String getPermissionName()
   :outertype: PermissionDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: PermissionDto

setBundleName
^^^^^^^^^^^^^

.. java:method:: public void setBundleName(String bundleName)
   :outertype: PermissionDto

setPermissionName
^^^^^^^^^^^^^^^^^

.. java:method:: public void setPermissionName(String permissionName)
   :outertype: PermissionDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: PermissionDto

