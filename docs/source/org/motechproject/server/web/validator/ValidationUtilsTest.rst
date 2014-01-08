.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.mockito.runners MockitoJUnitRunner

.. java:import:: org.springframework.validation Errors

.. java:import:: java.util List

ValidationUtilsTest
===================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: @RunWith public class ValidationUtilsTest

Fields
------
errors
^^^^^^

.. java:field:: @Mock  Errors errors
   :outertype: ValidationUtilsTest

Methods
-------
shouldValidateForLocalhostUrl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateForLocalhostUrl() throws Exception
   :outertype: ValidationUtilsTest

shouldValidateForUrl
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateForUrl() throws Exception
   :outertype: ValidationUtilsTest

shouldValidateIfDbUrlDbUsernameAndDbPasswordIsEmpty
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldValidateIfDbUrlDbUsernameAndDbPasswordIsEmpty() throws Exception
   :outertype: ValidationUtilsTest

