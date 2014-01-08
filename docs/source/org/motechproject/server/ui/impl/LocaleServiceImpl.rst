.. java:import:: org.apache.commons.lang LocaleUtils

.. java:import:: org.apache.commons.lang WordUtils

.. java:import:: org.eclipse.gemini.blueprint.context BundleContextAware

.. java:import:: org.motechproject.osgi.web ModuleRegistrationData

.. java:import:: org.motechproject.osgi.web UIFrameworkService

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.ui LocaleService

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core Authentication

.. java:import:: org.springframework.security.core.context SecurityContext

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.stereotype Service

.. java:import:: org.springframework.web.servlet.i18n CookieLocaleResolver

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.net URL

.. java:import:: java.util Collection

.. java:import:: java.util Enumeration

.. java:import:: java.util HashMap

.. java:import:: java.util Locale

.. java:import:: java.util Map

.. java:import:: java.util NavigableMap

.. java:import:: java.util Properties

.. java:import:: java.util TreeMap

LocaleServiceImpl
=================

.. java:package:: org.motechproject.server.ui.impl
   :noindex:

.. java:type:: @Service public class LocaleServiceImpl implements LocaleService, BundleContextAware

   Implementation of the \ ``LocaleService``\  interface. Uses the user service for operations related to user language setting/retrieval. It also falls back to a cookie locale resolver for not not logged in users(also users without a language set. It retrieves messages by loading them from registered modules.

Methods
-------
getAvailableLanguages
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public NavigableMap<String, String> getAvailableLanguages()
   :outertype: LocaleServiceImpl

getMessages
^^^^^^^^^^^

.. java:method:: @Override public Map<String, String> getMessages(HttpServletRequest request)
   :outertype: LocaleServiceImpl

getUserLocale
^^^^^^^^^^^^^

.. java:method:: @Override public Locale getUserLocale(HttpServletRequest request)
   :outertype: LocaleServiceImpl

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setBundleContext(BundleContext context)
   :outertype: LocaleServiceImpl

setUserLocale
^^^^^^^^^^^^^

.. java:method:: @Override public void setUserLocale(HttpServletRequest request, HttpServletResponse response, Locale locale)
   :outertype: LocaleServiceImpl

