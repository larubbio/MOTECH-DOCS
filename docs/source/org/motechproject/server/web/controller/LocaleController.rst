.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.util Locale

.. java:import:: java.util Map

.. java:import:: java.util NavigableMap

LocaleController
================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: @Controller public class LocaleController

   The \ ``LocaleController``\  class is responsible for handling requests connected with internationalization

Methods
-------
getAvailableLanguages
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public NavigableMap<String, String> getAvailableLanguages()
   :outertype: LocaleController

getLangLocalisation
^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Map<String, String> getLangLocalisation(HttpServletRequest request)
   :outertype: LocaleController

getUserLang
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String getUserLang(HttpServletRequest request)
   :outertype: LocaleController

setUserLang
^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void setUserLang(HttpServletRequest request, HttpServletResponse response, String language, String country, String variant)
   :outertype: LocaleController

