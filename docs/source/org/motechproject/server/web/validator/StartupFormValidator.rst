.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util ArrayList

.. java:import:: java.util List

StartupFormValidator
====================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: @Component public class StartupFormValidator

   StartupFormValidator validates user information during registration process

Constructors
------------
StartupFormValidator
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public StartupFormValidator()
   :outertype: StartupFormValidator

Methods
-------
add
^^^

.. java:method:: public void add(AbstractValidator validator)
   :outertype: StartupFormValidator

getValidators
^^^^^^^^^^^^^

.. java:method:: public List<AbstractValidator> getValidators()
   :outertype: StartupFormValidator

validate
^^^^^^^^

.. java:method:: public List<String> validate(StartupForm target)
   :outertype: StartupFormValidator

