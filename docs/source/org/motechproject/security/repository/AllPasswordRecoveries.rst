.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.security.domain PasswordRecovery

.. java:import:: java.util List

.. java:import:: java.util Locale

AllPasswordRecoveries
=====================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: public interface AllPasswordRecoveries

Methods
-------
add
^^^

.. java:method::  void add(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveries

allRecoveries
^^^^^^^^^^^^^

.. java:method::  List<PasswordRecovery> allRecoveries()
   :outertype: AllPasswordRecoveries

createRecovery
^^^^^^^^^^^^^^

.. java:method::  PasswordRecovery createRecovery(String username, String email, String token, DateTime expirationDate, Locale locale)
   :outertype: AllPasswordRecoveries

findForToken
^^^^^^^^^^^^

.. java:method::  PasswordRecovery findForToken(String token)
   :outertype: AllPasswordRecoveries

findForUser
^^^^^^^^^^^

.. java:method::  PasswordRecovery findForUser(String username)
   :outertype: AllPasswordRecoveries

getExpired
^^^^^^^^^^

.. java:method::  List<PasswordRecovery> getExpired()
   :outertype: AllPasswordRecoveries

remove
^^^^^^

.. java:method::  void remove(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveries

update
^^^^^^

.. java:method::  void update(PasswordRecovery passwordRecovery)
   :outertype: AllPasswordRecoveries

