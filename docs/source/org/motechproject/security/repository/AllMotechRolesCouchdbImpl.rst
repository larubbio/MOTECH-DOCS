.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.domain MotechRoleCouchdbImpl

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AllMotechRolesCouchdbImpl
=========================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @Component @View public class AllMotechRolesCouchdbImpl extends MotechBaseRepository<MotechRoleCouchdbImpl> implements AllMotechRoles

Constructors
------------
AllMotechRolesCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllMotechRolesCouchdbImpl(CouchDbConnector db)
   :outertype: AllMotechRolesCouchdbImpl

Methods
-------
add
^^^

.. java:method:: @Override public void add(MotechRole role)
   :outertype: AllMotechRolesCouchdbImpl

findByRoleName
^^^^^^^^^^^^^^

.. java:method:: @Override @View public MotechRole findByRoleName(String roleName)
   :outertype: AllMotechRolesCouchdbImpl

getRoles
^^^^^^^^

.. java:method:: @Override public List<MotechRole> getRoles()
   :outertype: AllMotechRolesCouchdbImpl

remove
^^^^^^

.. java:method:: @Override public void remove(MotechRole motechRole)
   :outertype: AllMotechRolesCouchdbImpl

update
^^^^^^

.. java:method:: @Override public void update(MotechRole motechRole)
   :outertype: AllMotechRolesCouchdbImpl

