.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.ex RoleHasUserException

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MotechRoleServiceImpl
=====================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class MotechRoleServiceImpl implements MotechRoleService

   Service to manage roles in Motech

Methods
-------
createRole
^^^^^^^^^^

.. java:method:: @Override public void createRole(RoleDto role)
   :outertype: MotechRoleServiceImpl

deleteRole
^^^^^^^^^^

.. java:method:: @Override public void deleteRole(RoleDto role)
   :outertype: MotechRoleServiceImpl

getRole
^^^^^^^

.. java:method:: @Override public RoleDto getRole(String roleName)
   :outertype: MotechRoleServiceImpl

getRoles
^^^^^^^^

.. java:method:: @Override public List<RoleDto> getRoles()
   :outertype: MotechRoleServiceImpl

updateRole
^^^^^^^^^^

.. java:method:: @Override public void updateRole(RoleDto role)
   :outertype: MotechRoleServiceImpl

