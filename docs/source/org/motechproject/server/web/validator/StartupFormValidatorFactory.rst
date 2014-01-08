.. java:import:: org.apache.commons.validator UrlValidator

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: org.springframework.stereotype Component

StartupFormValidatorFactory
===========================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: @Component public class StartupFormValidatorFactory

   Factory to create startUpFormValidator with requisite validators. If Admin User exists,the admin user is not created so the relevant validators are not added.

Methods
-------
getStartupFormValidator
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public StartupFormValidator getStartupFormValidator(StartupForm startupSettings, MotechUserService userService)
   :outertype: StartupFormValidatorFactory

