.. java:import:: java.util Objects

.. java:import:: java.util Properties

MdsSettingsDto
==============

.. java:package:: org.motechproject.mds.dto
   :noindex:

.. java:type:: public class MdsSettingsDto

   The \ ``MdsSettingDto``\  contains module settings.

Fields
------
MDS_DELETE_MODE_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MDS_DELETE_MODE_PROPERTY
   :outertype: MdsSettingsDto

MDS_EMPTY_TRASH_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MDS_EMPTY_TRASH_PROPERTY
   :outertype: MdsSettingsDto

MDS_PROPERTIES_FILE_NAME
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MDS_PROPERTIES_FILE_NAME
   :outertype: MdsSettingsDto

MDS_TIME_UNIT_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MDS_TIME_UNIT_PROPERTY
   :outertype: MdsSettingsDto

MDS_TIME_VALUE_PROPERTY
^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String MDS_TIME_VALUE_PROPERTY
   :outertype: MdsSettingsDto

Constructors
------------
MdsSettingsDto
^^^^^^^^^^^^^^

.. java:constructor:: public MdsSettingsDto()
   :outertype: MdsSettingsDto

MdsSettingsDto
^^^^^^^^^^^^^^

.. java:constructor:: public MdsSettingsDto(Properties properties)
   :outertype: MdsSettingsDto

MdsSettingsDto
^^^^^^^^^^^^^^

.. java:constructor:: public MdsSettingsDto(String deleteMode, String emptyTrash, String timeValue, String timeUnit)
   :outertype: MdsSettingsDto

MdsSettingsDto
^^^^^^^^^^^^^^

.. java:constructor:: public MdsSettingsDto(String deleteMode, Boolean emptyTrash, int timeValue, String timeUnit)
   :outertype: MdsSettingsDto

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: MdsSettingsDto

getDeleteMode
^^^^^^^^^^^^^

.. java:method:: public String getDeleteMode()
   :outertype: MdsSettingsDto

getEmptyTrash
^^^^^^^^^^^^^

.. java:method:: public Boolean getEmptyTrash()
   :outertype: MdsSettingsDto

getTimeUnit
^^^^^^^^^^^

.. java:method:: public String getTimeUnit()
   :outertype: MdsSettingsDto

getTimeValue
^^^^^^^^^^^^

.. java:method:: public int getTimeValue()
   :outertype: MdsSettingsDto

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: MdsSettingsDto

setDeleteMode
^^^^^^^^^^^^^

.. java:method:: public void setDeleteMode(String deleteMode)
   :outertype: MdsSettingsDto

setEmptyTrash
^^^^^^^^^^^^^

.. java:method:: public void setEmptyTrash(Boolean emptyTrash)
   :outertype: MdsSettingsDto

setTimeUnit
^^^^^^^^^^^

.. java:method:: public void setTimeUnit(String timeUnit)
   :outertype: MdsSettingsDto

setTimeValue
^^^^^^^^^^^^

.. java:method:: public void setTimeValue(int timeValue)
   :outertype: MdsSettingsDto

toProperties
^^^^^^^^^^^^

.. java:method:: public Properties toProperties()
   :outertype: MdsSettingsDto

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: MdsSettingsDto

