.. java:import:: org.apache.http HttpStatus

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.codehaus.jackson.node ObjectNode

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.email InitializeSettings

.. java:import:: org.motechproject.email.model SettingsDto

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.mail.javamail JavaMailSenderImpl

.. java:import:: org.springframework.test.web.server MockMvc

.. java:import:: org.springframework.test.web.server.setup MockMvcBuilders

.. java:import:: java.util Properties

SettingsControllerTest
======================

.. java:package:: org.motechproject.email.web
   :noindex:

.. java:type:: public class SettingsControllerTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: SettingsControllerTest

shouldChangeSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldChangeSettings() throws Exception
   :outertype: SettingsControllerTest

shouldNotChangeSettingsWhenHostIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotChangeSettingsWhenHostIsBlank() throws Exception
   :outertype: SettingsControllerTest

shouldNotChangeSettingsWhenPortIsBlank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotChangeSettingsWhenPortIsBlank() throws Exception
   :outertype: SettingsControllerTest

shouldNotChangeSettingsWhenPortIsNotNumeric
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotChangeSettingsWhenPortIsNotNumeric() throws Exception
   :outertype: SettingsControllerTest

shouldReturnSettingsDto
^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldReturnSettingsDto() throws Exception
   :outertype: SettingsControllerTest

