.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.lang.builder EqualsBuilder

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util Map

.. java:import:: java.util Objects

.. java:import:: java.util Properties

ModulePropertiesRecord
======================

.. java:package:: org.motechproject.config.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class ModulePropertiesRecord extends MotechBaseDataObject

   The \ ``ModulePropertiesRecord``\  class represents a database record of a certain module properties.

Fields
------
PROPERTIES_FILE_EXTENSION
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PROPERTIES_FILE_EXTENSION
   :outertype: ModulePropertiesRecord

Constructors
------------
ModulePropertiesRecord
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModulePropertiesRecord()
   :outertype: ModulePropertiesRecord

ModulePropertiesRecord
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModulePropertiesRecord(Map<String, String> properties, String module, String version, String bundle, String filename, boolean raw)
   :outertype: ModulePropertiesRecord

ModulePropertiesRecord
^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModulePropertiesRecord(Properties props, String module, String version, String bundle, String filename, boolean raw)
   :outertype: ModulePropertiesRecord

Methods
-------
buildFrom
^^^^^^^^^

.. java:method:: public static ModulePropertiesRecord buildFrom(File file)
   :outertype: ModulePropertiesRecord

equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: ModulePropertiesRecord

getBundle
^^^^^^^^^

.. java:method:: public String getBundle()
   :outertype: ModulePropertiesRecord

getFilename
^^^^^^^^^^^

.. java:method:: public String getFilename()
   :outertype: ModulePropertiesRecord

getModule
^^^^^^^^^

.. java:method:: public String getModule()
   :outertype: ModulePropertiesRecord

getProperties
^^^^^^^^^^^^^

.. java:method:: public Map<String, String> getProperties()
   :outertype: ModulePropertiesRecord

getVersion
^^^^^^^^^^

.. java:method:: public String getVersion()
   :outertype: ModulePropertiesRecord

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: ModulePropertiesRecord

isRaw
^^^^^

.. java:method:: public boolean isRaw()
   :outertype: ModulePropertiesRecord

sameAs
^^^^^^

.. java:method:: public boolean sameAs(MotechBaseDataObject dataObject)
   :outertype: ModulePropertiesRecord

setBundle
^^^^^^^^^

.. java:method:: public void setBundle(String bundle)
   :outertype: ModulePropertiesRecord

setFilename
^^^^^^^^^^^

.. java:method:: public void setFilename(String filename)
   :outertype: ModulePropertiesRecord

setModule
^^^^^^^^^

.. java:method:: public void setModule(String module)
   :outertype: ModulePropertiesRecord

setProperties
^^^^^^^^^^^^^

.. java:method:: public void setProperties(Map<String, String> properties)
   :outertype: ModulePropertiesRecord

setRaw
^^^^^^

.. java:method:: public void setRaw(boolean raw)
   :outertype: ModulePropertiesRecord

setVersion
^^^^^^^^^^

.. java:method:: public void setVersion(String version)
   :outertype: ModulePropertiesRecord

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: ModulePropertiesRecord

