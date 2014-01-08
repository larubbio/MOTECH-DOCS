.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: org.motechproject.security.domain MotechPermissionCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.repository AllMotechPermissions

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MotechPermissionServiceImpl
===========================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class MotechPermissionServiceImpl implements MotechPermissionService

   Implementation of the \ :java:ref:`MotechPermissionService`\  interface. Uses \ :java:ref:`AllMotechPermissions`\  in order to retrieve and persist permissions.

Methods
-------
addPermission
^^^^^^^^^^^^^

.. java:method:: @Override public void addPermission(PermissionDto permission)
   :outertype: MotechPermissionServiceImpl

deletePermission
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void deletePermission(String permissionName)
   :outertype: MotechPermissionServiceImpl

getPermissions
^^^^^^^^^^^^^^

.. java:method:: @Override public List<PermissionDto> getPermissions()
   :outertype: MotechPermissionServiceImpl

