.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.commons.lang.exception ExceptionUtils

.. java:import:: org.motechproject.admin.bundles ExtendedBundleInformation

.. java:import:: org.motechproject.admin.service ModuleAdminService

.. java:import:: org.motechproject.admin.service StatusMessageService

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.server.api BundleIcon

.. java:import:: org.motechproject.server.api BundleInformation

.. java:import:: org.osgi.framework BundleException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: org.springframework.web.multipart MultipartFile

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

.. java:import:: java.io Writer

.. java:import:: java.util List

BundleAdminController
=====================

.. java:package:: org.motechproject.admin.web.controller
   :noindex:

.. java:type:: @Controller public class BundleAdminController

Methods
-------
getBundle
^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public BundleInformation getBundle(long bundleId)
   :outertype: BundleAdminController

getBundleDetails
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public ExtendedBundleInformation getBundleDetails(long bundleId)
   :outertype: BundleAdminController

getBundleIcon
^^^^^^^^^^^^^

.. java:method:: @RequestMapping public void getBundleIcon(long bundleId, HttpServletResponse response) throws IOException
   :outertype: BundleAdminController

getBundles
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<BundleInformation> getBundles()
   :outertype: BundleAdminController

handleBundleException
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler public void handleBundleException(HttpServletResponse response, Exception ex) throws IOException
   :outertype: BundleAdminController

restartBundle
^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public BundleInformation restartBundle(long bundleId) throws BundleException
   :outertype: BundleAdminController

startBundle
^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public BundleInformation startBundle(long bundleId) throws BundleException
   :outertype: BundleAdminController

stopBundle
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public BundleInformation stopBundle(long bundleId) throws BundleException
   :outertype: BundleAdminController

uninstallBundle
^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void uninstallBundle(long bundleId) throws BundleException
   :outertype: BundleAdminController

uninstallBundleWithConfig
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void uninstallBundleWithConfig(long bundleId) throws BundleException
   :outertype: BundleAdminController

uploadBundle
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public BundleInformation uploadBundle(String moduleSource, String moduleId, MultipartFile bundleFile, String startBundle)
   :outertype: BundleAdminController

