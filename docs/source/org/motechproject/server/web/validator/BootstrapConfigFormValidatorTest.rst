.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.server.web.form BootstrapConfigForm

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.validation Errors

BootstrapConfigFormValidatorTest
================================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class BootstrapConfigFormValidatorTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: BootstrapConfigFormValidatorTest

shouldValidateForConfigSource
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateForConfigSource()
   :outertype: BootstrapConfigFormValidatorTest

shouldValidateForDbUrlFormatIfNotEmpty
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateForDbUrlFormatIfNotEmpty()
   :outertype: BootstrapConfigFormValidatorTest

shouldValidateOnlyForEmptyFields
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateOnlyForEmptyFields()
   :outertype: BootstrapConfigFormValidatorTest

