.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.motechproject.config.service ConfigurationService

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Properties

SettingsFacadeTest
==================

.. java:package:: org.motechproject.server.config
   :noindex:

.. java:type:: public class SettingsFacadeTest

Fields
------
configurationService
^^^^^^^^^^^^^^^^^^^^

.. java:field:: @Mock  ConfigurationService configurationService
   :outertype: SettingsFacadeTest

props
^^^^^

.. java:field:: @Mock  Properties props
   :outertype: SettingsFacadeTest

settingsFacade
^^^^^^^^^^^^^^

.. java:field::  SettingsFacade settingsFacade
   :outertype: SettingsFacadeTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: SettingsFacadeTest

shouldMarkConfigurationSettingsNotRegisteredWhenMotechConfigExceptionIsThrown
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldMarkConfigurationSettingsNotRegisteredWhenMotechConfigExceptionIsThrown() throws IOException
   :outertype: SettingsFacadeTest

testAsProperties
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testAsProperties()
   :outertype: SettingsFacadeTest

testGetConfigNoService
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetConfigNoService()
   :outertype: SettingsFacadeTest

testGetConfigWithService
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void testGetConfigWithService() throws IOException
   :outertype: SettingsFacadeTest

testSetConfig
^^^^^^^^^^^^^

.. java:method:: @Test public void testSetConfig() throws IOException
   :outertype: SettingsFacadeTest

