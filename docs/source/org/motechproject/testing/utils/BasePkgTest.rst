.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.lang ArrayUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.apache.http HttpResponse

.. java:import:: org.apache.http HttpStatus

.. java:import:: org.apache.http NameValuePair

.. java:import:: org.apache.http.client.entity UrlEncodedFormEntity

.. java:import:: org.apache.http.client.methods HttpPost

.. java:import:: org.apache.http.message BasicNameValuePair

.. java:import:: org.junit After

.. java:import:: org.junit Before

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.io File

.. java:import:: java.io FileOutputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io OutputStream

.. java:import:: java.util ArrayList

.. java:import:: java.util List

BasePkgTest
===========

.. java:package:: org.motechproject.testing.utils
   :noindex:

.. java:type:: public abstract class BasePkgTest

Methods
-------
cleanUp
^^^^^^^

.. java:method:: @After public void cleanUp()
   :outertype: BasePkgTest

getBaseUrl
^^^^^^^^^^

.. java:method:: protected String getBaseUrl()
   :outertype: BasePkgTest

getChrootDirProp
^^^^^^^^^^^^^^^^

.. java:method:: public abstract String getChrootDirProp()
   :outertype: BasePkgTest

getLogger
^^^^^^^^^

.. java:method:: protected static Logger getLogger()
   :outertype: BasePkgTest

getTenantBaseUrl
^^^^^^^^^^^^^^^^

.. java:method:: protected String getTenantBaseUrl()
   :outertype: BasePkgTest

installScript
^^^^^^^^^^^^^

.. java:method:: protected void installScript(String name) throws IOException
   :outertype: BasePkgTest

login
^^^^^

.. java:method:: protected void login() throws InterruptedException, IOException
   :outertype: BasePkgTest

readErrors
^^^^^^^^^^

.. java:method:: protected String readErrors() throws IOException
   :outertype: BasePkgTest

runScript
^^^^^^^^^

.. java:method:: protected int runScript(String scriptName, boolean passPorts, String... attrs) throws IOException, InterruptedException
   :outertype: BasePkgTest

setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: BasePkgTest

submitBootstrapData
^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void submitBootstrapData() throws IOException, InterruptedException
   :outertype: BasePkgTest

submitStartupData
^^^^^^^^^^^^^^^^^

.. java:method:: protected void submitStartupData() throws IOException, InterruptedException
   :outertype: BasePkgTest

testInstall
^^^^^^^^^^^

.. java:method:: protected void testInstall() throws IOException, InterruptedException
   :outertype: BasePkgTest

testUninstall
^^^^^^^^^^^^^

.. java:method:: protected void testUninstall() throws IOException, InterruptedException
   :outertype: BasePkgTest

