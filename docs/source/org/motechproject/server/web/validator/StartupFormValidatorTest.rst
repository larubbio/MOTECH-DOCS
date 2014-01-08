.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.security.service MotechUserService

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.util List

StartupFormValidatorTest
========================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class StartupFormValidatorTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: StartupFormValidatorTest

shouldRejectEmptyFields
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectEmptyFields()
   :outertype: StartupFormValidatorTest

shouldRejectEmptyUserFieldsWhenLoginModeIsOpenId
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectEmptyUserFieldsWhenLoginModeIsOpenId()
   :outertype: StartupFormValidatorTest

shouldRejectEmptyUserFieldsWhenLoginModeIsRepository
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldRejectEmptyUserFieldsWhenLoginModeIsRepository()
   :outertype: StartupFormValidatorTest

