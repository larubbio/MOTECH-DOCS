.. java:import:: com.google.common.net HttpHeaders

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.admin.domain AdminSettings

.. java:import:: org.motechproject.admin.service SettingsService

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.admin.settings Settings

.. java:import:: org.motechproject.admin.settings SettingsOption

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.text SimpleDateFormat

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util Date

.. java:import:: java.util List

.. java:import:: java.util Map

SettingsController
==================

.. java:package:: org.motechproject.admin.web.controller
   :noindex:

.. java:type:: @Controller public class SettingsController

   Class responsible for communication between frontend and backend

Methods
-------
exportConfig
^^^^^^^^^^^^

.. java:method:: @RequestMapping public void exportConfig(HttpServletResponse response) throws IOException
   :outertype: SettingsController

getBundleSettings
^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<Settings> getBundleSettings(long bundleId) throws IOException
   :outertype: SettingsController

getBundlesWithSettings
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping @ResponseBody public List<String> getBundlesWithSettings()
   :outertype: SettingsController

getPlatformSettings
^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public AdminSettings getPlatformSettings()
   :outertype: SettingsController

getRawFilenames
^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<String> getRawFilenames(long bundleId)
   :outertype: SettingsController

handleException
^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @ExceptionHandler public void handleException(Exception e)
   :outertype: SettingsController

saveBundleSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveBundleSettings(long bundleId, Settings bundleSettings) throws IOException
   :outertype: SettingsController

saveNewSettings
^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void saveNewSettings(HttpServletRequest request)
   :outertype: SettingsController

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void savePlatformSettings(Settings platformSettings)
   :outertype: SettingsController

savePlatformSettings
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void savePlatformSettings(Settings platformSettings) throws IOException
   :outertype: SettingsController

uploadRawFile
^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping  void uploadRawFile(long bundleId, String filename, MultipartFile file)
   :outertype: SettingsController

uploadSettingsFile
^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void uploadSettingsFile(MultipartFile settingsFile)
   :outertype: SettingsController

uploadSettingsLocation
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void uploadSettingsLocation(String location) throws IOException
   :outertype: SettingsController

