.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.net URL

Header
======

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class Header

Constructors
------------
Header
^^^^^^

.. java:constructor:: @Autowired public Header(BundleContext bundleContext)
   :outertype: Header

Methods
-------
asString
^^^^^^^^

.. java:method:: public String asString()
   :outertype: Header

setResourcePath
^^^^^^^^^^^^^^^

.. java:method:: public void setResourcePath(String resourcePath)
   :outertype: Header

