.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: org.motechproject.security.domain MotechPermissionCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.repository AllMotechPermissions

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: java.io IOException

.. java:import:: java.util Arrays

.. java:import:: java.util List

Initialize
==========

.. java:package:: org.motechproject.security
   :noindex:

.. java:type:: public class Initialize

   This class initializes some of the Motech Permissions, initializes User Admin role, as well as fixes a bug with "Admin User" role name.

Methods
-------
initialize
^^^^^^^^^^

.. java:method:: @Autowired public void initialize(CouchDbConnector db) throws IOException
   :outertype: Initialize

