.. java:import:: org.hamcrest.core IsEqual

.. java:import:: org.junit Test

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: org.springframework.core.io ClassPathResource

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.core.io UrlResource

.. java:import:: java.io File

.. java:import:: java.io IOException

.. java:import:: java.net MalformedURLException

ConfigLocationTest
==================

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public class ConfigLocationTest

Methods
-------
shouldAppendFileSeparatorIfGivenLocationDoesNotEndWithOne
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAppendFileSeparatorIfGivenLocationDoesNotEndWithOne()
   :outertype: ConfigLocationTest

shouldConvertClasspathLocationToResource
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldConvertClasspathLocationToResource()
   :outertype: ConfigLocationTest

shouldConvertFileLocationToResource
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldConvertFileLocationToResource() throws IOException
   :outertype: ConfigLocationTest

shouldGetFileForGivenFileAccessType
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetFileForGivenFileAccessType()
   :outertype: ConfigLocationTest

shouldGetFileRelativeToConfigLocationGivenAnAccessType
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldGetFileRelativeToConfigLocationGivenAnAccessType() throws IOException
   :outertype: ConfigLocationTest

shouldThrowExceptionWhenFileAccessCheckThrowsError
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenFileAccessCheckThrowsError() throws IOException
   :outertype: ConfigLocationTest

shouldThrowExceptionWhenFileIsNotWritableWhenAskedForWritableAccessType
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenFileIsNotWritableWhenAskedForWritableAccessType() throws IOException
   :outertype: ConfigLocationTest

shouldThrowExceptionWhenInvalidConfigLocationIsGiven
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldThrowExceptionWhenInvalidConfigLocationIsGiven() throws MalformedURLException
   :outertype: ConfigLocationTest

