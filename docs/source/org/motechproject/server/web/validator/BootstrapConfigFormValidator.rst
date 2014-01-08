.. java:import:: org.motechproject.config.core.domain ConfigSource

.. java:import:: org.motechproject.server.web.form BootstrapConfigForm

.. java:import:: org.springframework.validation Errors

.. java:import:: org.springframework.validation Validator

BootstrapConfigFormValidator
============================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class BootstrapConfigFormValidator implements Validator

   Validator that validates bootstrap configuration input by the user in the bootstrap config UI.

Fields
------
ERROR_REQUIRED
^^^^^^^^^^^^^^

.. java:field:: static final String ERROR_REQUIRED
   :outertype: BootstrapConfigFormValidator

Methods
-------
supports
^^^^^^^^

.. java:method:: @Override public boolean supports(Class<?> clazz)
   :outertype: BootstrapConfigFormValidator

validate
^^^^^^^^

.. java:method:: @Override public void validate(Object target, Errors errors)
   :outertype: BootstrapConfigFormValidator

