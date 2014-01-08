.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.security.model RoleDto

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util List

SecurityRoleLoader
==================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public class SecurityRoleLoader

Constructors
------------
SecurityRoleLoader
^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SecurityRoleLoader(MotechRoleService roleService)
   :outertype: SecurityRoleLoader

Methods
-------
loadRoles
^^^^^^^^^

.. java:method:: public void loadRoles(ApplicationContext applicationContext)
   :outertype: SecurityRoleLoader

