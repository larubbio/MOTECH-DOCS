.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: java.util List

.. java:import:: java.util Locale

MotechUserCouchdbImpl
=====================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class MotechUserCouchdbImpl extends MotechBaseDataObject implements MotechUser

   CouchDb implementation of the \ :java:ref:`MotechUser`\ .

Fields
------
DOC_TYPE
^^^^^^^^

.. java:field:: public static final String DOC_TYPE
   :outertype: MotechUserCouchdbImpl

Constructors
------------
MotechUserCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechUserCouchdbImpl()
   :outertype: MotechUserCouchdbImpl

MotechUserCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechUserCouchdbImpl(String userName, String password, String email, String externalId, List<String> roles, String openId, Locale locale)
   :outertype: MotechUserCouchdbImpl

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: MotechUserCouchdbImpl

getEmail
^^^^^^^^

.. java:method:: public String getEmail()
   :outertype: MotechUserCouchdbImpl

getExternalId
^^^^^^^^^^^^^

.. java:method:: public String getExternalId()
   :outertype: MotechUserCouchdbImpl

getLocale
^^^^^^^^^

.. java:method:: public Locale getLocale()
   :outertype: MotechUserCouchdbImpl

getOpenId
^^^^^^^^^

.. java:method:: public String getOpenId()
   :outertype: MotechUserCouchdbImpl

getPassword
^^^^^^^^^^^

.. java:method:: public String getPassword()
   :outertype: MotechUserCouchdbImpl

getRoles
^^^^^^^^

.. java:method:: public List<String> getRoles()
   :outertype: MotechUserCouchdbImpl

getUserName
^^^^^^^^^^^

.. java:method:: public String getUserName()
   :outertype: MotechUserCouchdbImpl

hasRole
^^^^^^^

.. java:method:: @Override public boolean hasRole(String role)
   :outertype: MotechUserCouchdbImpl

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: MotechUserCouchdbImpl

isActive
^^^^^^^^

.. java:method:: public boolean isActive()
   :outertype: MotechUserCouchdbImpl

setActive
^^^^^^^^^

.. java:method:: public void setActive(boolean active)
   :outertype: MotechUserCouchdbImpl

setEmail
^^^^^^^^

.. java:method:: public void setEmail(String email)
   :outertype: MotechUserCouchdbImpl

setExternalId
^^^^^^^^^^^^^

.. java:method:: public void setExternalId(String externalId)
   :outertype: MotechUserCouchdbImpl

setLocale
^^^^^^^^^

.. java:method:: public void setLocale(Locale locale)
   :outertype: MotechUserCouchdbImpl

setOpenId
^^^^^^^^^

.. java:method:: public void setOpenId(String openId)
   :outertype: MotechUserCouchdbImpl

setPassword
^^^^^^^^^^^

.. java:method:: public void setPassword(String password)
   :outertype: MotechUserCouchdbImpl

setRoles
^^^^^^^^

.. java:method:: public void setRoles(List<String> roles)
   :outertype: MotechUserCouchdbImpl

setUserName
^^^^^^^^^^^

.. java:method:: public void setUserName(String userName)
   :outertype: MotechUserCouchdbImpl

