.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain PasswordRecovery

EmailSender
===========

.. java:package:: org.motechproject.security.email
   :noindex:

.. java:type:: public interface EmailSender

Methods
-------
sendLoginInfo
^^^^^^^^^^^^^

.. java:method::  void sendLoginInfo(MotechUser user, String password)
   :outertype: EmailSender

sendOneTimeToken
^^^^^^^^^^^^^^^^

.. java:method::  void sendOneTimeToken(PasswordRecovery recovery)
   :outertype: EmailSender

sendResecoveryEmail
^^^^^^^^^^^^^^^^^^^

.. java:method::  void sendResecoveryEmail(PasswordRecovery recovery)
   :outertype: EmailSender

