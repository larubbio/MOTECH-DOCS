.. java:import:: org.ektorp BulkDeleteDocument

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.config.domain ModulePropertiesRecord

.. java:import:: java.util Arrays

.. java:import:: java.util Collection

.. java:import:: java.util Collections

.. java:import:: java.util List

AllModulePropertiesTest
=======================

.. java:package:: org.motechproject.config.repository
   :noindex:

.. java:type:: public class AllModulePropertiesTest

Fields
------
db
^^

.. java:field:: @Mock  CouchDbConnector db
   :outertype: AllModulePropertiesTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: AllModulePropertiesTest

shouldBulkAddOrUpdate
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBulkAddOrUpdate()
   :outertype: AllModulePropertiesTest

shouldBulkDelete
^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldBulkDelete()
   :outertype: AllModulePropertiesTest

shouldNotBulkAddOrUpdate
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotBulkAddOrUpdate()
   :outertype: AllModulePropertiesTest

shouldNotBulkDelete
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotBulkDelete()
   :outertype: AllModulePropertiesTest

