.. java:import:: java.io Serializable

.. java:import:: java.util List

.. java:import:: java.util Locale

MotechUserProfile
=================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: public class MotechUserProfile implements Serializable

Constructors
------------
MotechUserProfile
^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechUserProfile(MotechUser motechUser)
   :outertype: MotechUserProfile

Methods
-------
getActive
^^^^^^^^^

.. java:method:: public Boolean getActive()
   :outertype: MotechUserProfile

getExternalId
^^^^^^^^^^^^^

.. java:method:: public String getExternalId()
   :outertype: MotechUserProfile

getLocale
^^^^^^^^^

.. java:method:: public Locale getLocale()
   :outertype: MotechUserProfile

getRoles
^^^^^^^^

.. java:method:: public List<String> getRoles()
   :outertype: MotechUserProfile

getUserName
^^^^^^^^^^^

.. java:method:: public String getUserName()
   :outertype: MotechUserProfile

hasRole
^^^^^^^

.. java:method:: public boolean hasRole(String role)
   :outertype: MotechUserProfile

