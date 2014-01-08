.. java:import:: org.apache.commons.validator UrlValidator

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util List

OpenIdUserValidator
===================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class OpenIdUserValidator implements AbstractValidator

   Validates presence of OpenId related field values Also validates provider URL

Constructors
------------
OpenIdUserValidator
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public OpenIdUserValidator(UrlValidator urlValidator)
   :outertype: OpenIdUserValidator

Methods
-------
validate
^^^^^^^^

.. java:method:: @Override public void validate(StartupForm target, List<String> errors)
   :outertype: OpenIdUserValidator

