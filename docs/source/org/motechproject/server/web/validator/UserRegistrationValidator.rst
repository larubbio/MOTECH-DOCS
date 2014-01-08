.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util List

UserRegistrationValidator
=========================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class UserRegistrationValidator implements AbstractValidator

   Validator to validate user registration details. Delegates to either @OpenIdUserValidator or @UserRegistrationValidator depending on login mode preference.

Constructors
------------
UserRegistrationValidator
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public UserRegistrationValidator(PersistedUserValidator persistedUserValidator, OpenIdUserValidator openIdUserValidator)
   :outertype: UserRegistrationValidator

Methods
-------
validate
^^^^^^^^

.. java:method:: @Override public void validate(StartupForm target, List<String> errors)
   :outertype: UserRegistrationValidator

