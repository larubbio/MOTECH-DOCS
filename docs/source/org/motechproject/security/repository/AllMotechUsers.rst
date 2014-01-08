.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: java.util List

AllMotechUsers
==============

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: public interface AllMotechUsers

Methods
-------
add
^^^

.. java:method::  void add(MotechUser user)
   :outertype: AllMotechUsers

addOpenIdUser
^^^^^^^^^^^^^

.. java:method::  void addOpenIdUser(MotechUser user)
   :outertype: AllMotechUsers

checkUserAuthorisation
^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  boolean checkUserAuthorisation(String userName, String password)
   :outertype: AllMotechUsers

findByRole
^^^^^^^^^^

.. java:method::  List<? extends MotechUser> findByRole(String role)
   :outertype: AllMotechUsers

findByUserName
^^^^^^^^^^^^^^

.. java:method::  MotechUser findByUserName(String userName)
   :outertype: AllMotechUsers

findUserByEmail
^^^^^^^^^^^^^^^

.. java:method::  MotechUser findUserByEmail(String email)
   :outertype: AllMotechUsers

findUserByOpenId
^^^^^^^^^^^^^^^^

.. java:method::  MotechUser findUserByOpenId(String openId)
   :outertype: AllMotechUsers

getOpenIdUsers
^^^^^^^^^^^^^^

.. java:method::  List<MotechUser> getOpenIdUsers()
   :outertype: AllMotechUsers

getUsers
^^^^^^^^

.. java:method::  List<MotechUser> getUsers()
   :outertype: AllMotechUsers

remove
^^^^^^

.. java:method::  void remove(MotechUser motechUser)
   :outertype: AllMotechUsers

update
^^^^^^

.. java:method::  void update(MotechUser motechUser)
   :outertype: AllMotechUsers

