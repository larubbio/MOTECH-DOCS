.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito InjectMocks

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.commons.couchdb.service.impl CouchDbManagerImpl

.. java:import:: org.motechproject.config.core.constants ConfigurationConstants

.. java:import:: org.motechproject.server.config.domain SettingsRecord

.. java:import:: org.motechproject.server.config.repository AllSettings

.. java:import:: org.motechproject.server.config.service ConfigLoader

.. java:import:: org.motechproject.server.config.service PlatformSettingsService

.. java:import:: java.io IOException

.. java:import:: java.util Properties

PlatformSettingsServiceImplTest
===============================

.. java:package:: org.motechproject.server.config.service.impl
   :noindex:

.. java:type:: public class PlatformSettingsServiceImplTest

Fields
------
allSettings
^^^^^^^^^^^

.. java:field:: @Mock  AllSettings allSettings
   :outertype: PlatformSettingsServiceImplTest

configLoader
^^^^^^^^^^^^

.. java:field:: @Mock  ConfigLoader configLoader
   :outertype: PlatformSettingsServiceImplTest

couchDbManager
^^^^^^^^^^^^^^

.. java:field:: @Mock  CouchDbManagerImpl couchDbManager
   :outertype: PlatformSettingsServiceImplTest

platformSettingsService
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: @InjectMocks  PlatformSettingsService platformSettingsService
   :outertype: PlatformSettingsServiceImplTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: PlatformSettingsServiceImplTest

testExport
^^^^^^^^^^

.. java:method:: @Test public void testExport() throws IOException
   :outertype: PlatformSettingsServiceImplTest

