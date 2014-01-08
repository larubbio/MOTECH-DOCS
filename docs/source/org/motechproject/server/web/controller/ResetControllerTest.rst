.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.server.web.dto ResetViewData

.. java:import:: org.motechproject.server.web.validator ResetFormValidator

.. java:import:: org.motechproject.security.ex InvalidTokenException

.. java:import:: org.motechproject.security.service PasswordRecoveryService

.. java:import:: org.motechproject.server.web.form ResetForm

.. java:import:: org.springframework.web.servlet ModelAndView

.. java:import:: org.springframework.web.servlet.i18n CookieLocaleResolver

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.util Arrays

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Locale

ResetControllerTest
===================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: public class ResetControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: ResetControllerTest

testInvalidTokenOnView
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testInvalidTokenOnView()
   :outertype: ResetControllerTest

testReset
^^^^^^^^^

.. java:method:: @Test public void testReset() throws InvalidTokenException
   :outertype: ResetControllerTest

testResetInvalidToken
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testResetInvalidToken() throws InvalidTokenException
   :outertype: ResetControllerTest

testValidView
^^^^^^^^^^^^^

.. java:method:: @Test public void testValidView()
   :outertype: ResetControllerTest

testValidationErrors
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testValidationErrors()
   :outertype: ResetControllerTest

