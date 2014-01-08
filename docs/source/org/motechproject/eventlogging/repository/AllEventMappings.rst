.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.eventlogging.domain MappingsJson

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io InputStream

.. java:import:: java.lang.reflect Type

.. java:import:: java.util List

AllEventMappings
================

.. java:package:: org.motechproject.eventlogging.repository
   :noindex:

.. java:type:: @Component public class AllEventMappings

Fields
------
MAPPING_FILE_NAME
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MAPPING_FILE_NAME
   :outertype: AllEventMappings

Constructors
------------
AllEventMappings
^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AllEventMappings(SettingsFacade settings)
   :outertype: AllEventMappings

Methods
-------
getAllMappings
^^^^^^^^^^^^^^

.. java:method:: public List<MappingsJson> getAllMappings()
   :outertype: AllEventMappings

