.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: java.util List

AdminSettings
=============

.. java:package:: org.motechproject.admin.domain
   :noindex:

.. java:type:: public class AdminSettings

   \ ``AdminSettings``\  class is used to store settings for Admin module and specifies that these settings are read-only (by checking config source from bootstrap)

Constructors
------------
AdminSettings
^^^^^^^^^^^^^

.. java:constructor:: public AdminSettings(List<Settings> settingsList, boolean readOnly)
   :outertype: AdminSettings

Methods
-------
getSettingsList
^^^^^^^^^^^^^^^

.. java:method:: public List<Settings> getSettingsList()
   :outertype: AdminSettings

isReadOnly
^^^^^^^^^^

.. java:method:: public boolean isReadOnly()
   :outertype: AdminSettings

setReadOnly
^^^^^^^^^^^

.. java:method:: public void setReadOnly(boolean readOnly)
   :outertype: AdminSettings

setSettingsList
^^^^^^^^^^^^^^^

.. java:method:: public void setSettingsList(List<Settings> settingsList)
   :outertype: AdminSettings

