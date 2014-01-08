.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.security.model UserDto

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util ArrayList

.. java:import:: java.util List

PersistedUserValidatorTest
==========================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class PersistedUserValidatorTest

Methods
-------
before
^^^^^^

.. java:method:: @Before public void before()
   :outertype: PersistedUserValidatorTest

shouldRejectEmailIfInUse
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectEmailIfInUse()
   :outertype: PersistedUserValidatorTest

shouldRejectInvalidEmail
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectInvalidEmail()
   :outertype: PersistedUserValidatorTest

shouldRejectOnlyUserIfUserExistsAndIsRegisteredWithIdenticalEmail
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectOnlyUserIfUserExistsAndIsRegisteredWithIdenticalEmail()
   :outertype: PersistedUserValidatorTest

shouldRejectPasswordIfConfirmPasswordValueIsDifferent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectPasswordIfConfirmPasswordValueIsDifferent()
   :outertype: PersistedUserValidatorTest

shouldRejectUserIfUserExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectUserIfUserExists()
   :outertype: PersistedUserValidatorTest

shouldValidateFieldsAndRejectEmptyFields
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateFieldsAndRejectEmptyFields()
   :outertype: PersistedUserValidatorTest

