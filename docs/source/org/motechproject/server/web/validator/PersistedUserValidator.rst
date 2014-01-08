.. java:import:: org.apache.commons.validator EmailValidator

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util List

PersistedUserValidator
======================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class PersistedUserValidator implements AbstractValidator

   Validates presence of admin user registration fields. Checks existence of user with identical name Checks existence of user with identical email Checks that password and confirmed password field are same.

Constructors
------------
PersistedUserValidator
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public PersistedUserValidator(MotechUserService userService)
   :outertype: PersistedUserValidator

Methods
-------
validate
^^^^^^^^

.. java:method:: @Override public void validate(StartupForm target, List<String> errors)
   :outertype: PersistedUserValidator

