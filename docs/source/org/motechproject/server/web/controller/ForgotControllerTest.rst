.. java:import:: org.hamcrest.core Is

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.mockito MockitoAnnotations

.. java:import:: org.motechproject.security.ex UserNotFoundException

.. java:import:: org.motechproject.security.service PasswordRecoveryService

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.motechproject.server.config.domain LoginMode

.. java:import:: org.motechproject.server.config.domain MotechSettings

.. java:import:: org.motechproject.server.web.dto ForgotViewData

.. java:import:: org.springframework.web.servlet.i18n CookieLocaleResolver

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: java.util Locale

ForgotControllerTest
====================

.. java:package:: org.motechproject.server.web.controller
   :noindex:

.. java:type:: public class ForgotControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: ForgotControllerTest

tesValidView
^^^^^^^^^^^^

.. java:method:: @Test public void tesValidView()
   :outertype: ForgotControllerTest

testForgotPost
^^^^^^^^^^^^^^

.. java:method:: @Test public void testForgotPost() throws UserNotFoundException
   :outertype: ForgotControllerTest

testInvalidEmail
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testInvalidEmail() throws UserNotFoundException
   :outertype: ForgotControllerTest

