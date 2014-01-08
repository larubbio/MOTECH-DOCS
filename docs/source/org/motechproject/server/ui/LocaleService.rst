.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.util Locale

.. java:import:: java.util Map

.. java:import:: java.util NavigableMap

LocaleService
=============

.. java:package:: org.motechproject.server.ui
   :noindex:

.. java:type:: public interface LocaleService

   A service responsible for localization. Allows retrieval/settings of user language as well as retrieving localized messages for a user request. Can also be used to retrieve a list of usable languages.

Methods
-------
getAvailableLanguages
^^^^^^^^^^^^^^^^^^^^^

.. java:method::  NavigableMap<String, String> getAvailableLanguages()
   :outertype: LocaleService

getMessages
^^^^^^^^^^^

.. java:method::  Map<String, String> getMessages(HttpServletRequest request)
   :outertype: LocaleService

getUserLocale
^^^^^^^^^^^^^

.. java:method::  Locale getUserLocale(HttpServletRequest request)
   :outertype: LocaleService

setUserLocale
^^^^^^^^^^^^^

.. java:method::  void setUserLocale(HttpServletRequest request, HttpServletResponse response, Locale locale)
   :outertype: LocaleService

