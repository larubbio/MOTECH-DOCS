.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.security.domain MotechPermission

.. java:import:: org.motechproject.security.domain MotechPermissionCouchdbImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllMotechPermissionsCouchdbImpl
===============================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @Component @View public class AllMotechPermissionsCouchdbImpl extends MotechBaseRepository<MotechPermissionCouchdbImpl> implements AllMotechPermissions

   CouchDb implementation of the \ :java:ref:`AllMotechPermissions`\  interface.

Constructors
------------
AllMotechPermissionsCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllMotechPermissionsCouchdbImpl(CouchDbConnector db)
   :outertype: AllMotechPermissionsCouchdbImpl

Methods
-------
add
^^^

.. java:method:: @Override public void add(MotechPermission permission)
   :outertype: AllMotechPermissionsCouchdbImpl

delete
^^^^^^

.. java:method:: @Override public void delete(MotechPermission permission)
   :outertype: AllMotechPermissionsCouchdbImpl

findByPermissionName
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override @View public MotechPermission findByPermissionName(String permissionName)
   :outertype: AllMotechPermissionsCouchdbImpl

getPermissions
^^^^^^^^^^^^^^

.. java:method:: @Override public List<MotechPermission> getPermissions()
   :outertype: AllMotechPermissionsCouchdbImpl

