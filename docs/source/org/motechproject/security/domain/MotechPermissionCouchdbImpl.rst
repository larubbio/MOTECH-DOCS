.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

MotechPermissionCouchdbImpl
===========================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class MotechPermissionCouchdbImpl extends MotechBaseDataObject implements MotechPermission

   CouchDb implementation of \ :java:ref:`MotechPermission`\ .

Fields
------
DOC_TYPE
^^^^^^^^

.. java:field:: public static final String DOC_TYPE
   :outertype: MotechPermissionCouchdbImpl

Constructors
------------
MotechPermissionCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechPermissionCouchdbImpl()
   :outertype: MotechPermissionCouchdbImpl

MotechPermissionCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechPermissionCouchdbImpl(String permissionName, String bundleName)
   :outertype: MotechPermissionCouchdbImpl

Methods
-------
getBundleName
^^^^^^^^^^^^^

.. java:method:: public String getBundleName()
   :outertype: MotechPermissionCouchdbImpl

getPermissionName
^^^^^^^^^^^^^^^^^

.. java:method:: public String getPermissionName()
   :outertype: MotechPermissionCouchdbImpl

setBundleName
^^^^^^^^^^^^^

.. java:method:: public void setBundleName(String bundleName)
   :outertype: MotechPermissionCouchdbImpl

setPermissionName
^^^^^^^^^^^^^^^^^

.. java:method:: public void setPermissionName(String permissionName)
   :outertype: MotechPermissionCouchdbImpl

