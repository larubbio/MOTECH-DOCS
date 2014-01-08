.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: java.util List

MotechRoleCouchdbImpl
=====================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class MotechRoleCouchdbImpl extends MotechBaseDataObject implements MotechRole

   Represent Motech user roles, with persistence in CouchDB.

Fields
------
DOC_TYPE
^^^^^^^^

.. java:field:: public static final String DOC_TYPE
   :outertype: MotechRoleCouchdbImpl

Constructors
------------
MotechRoleCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechRoleCouchdbImpl()
   :outertype: MotechRoleCouchdbImpl

MotechRoleCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechRoleCouchdbImpl(String roleName, List<String> permissionNames, boolean deletable)
   :outertype: MotechRoleCouchdbImpl

Methods
-------
getPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getPermissionNames()
   :outertype: MotechRoleCouchdbImpl

getRoleName
^^^^^^^^^^^

.. java:method:: public String getRoleName()
   :outertype: MotechRoleCouchdbImpl

hasPermission
^^^^^^^^^^^^^

.. java:method:: @Override public boolean hasPermission(String permissionName)
   :outertype: MotechRoleCouchdbImpl

isDeletable
^^^^^^^^^^^

.. java:method:: public boolean isDeletable()
   :outertype: MotechRoleCouchdbImpl

removePermission
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void removePermission(String permissionName)
   :outertype: MotechRoleCouchdbImpl

setDeletable
^^^^^^^^^^^^

.. java:method:: public void setDeletable(boolean deletable)
   :outertype: MotechRoleCouchdbImpl

setPermissionNames
^^^^^^^^^^^^^^^^^^

.. java:method:: public void setPermissionNames(List<String> permissionNames)
   :outertype: MotechRoleCouchdbImpl

setRoleName
^^^^^^^^^^^

.. java:method:: public void setRoleName(String roleName)
   :outertype: MotechRoleCouchdbImpl

