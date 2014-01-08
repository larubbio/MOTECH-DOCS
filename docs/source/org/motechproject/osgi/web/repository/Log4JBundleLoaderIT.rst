.. java:import:: org.apache.log4j LogManager

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.osgi.web Log4JBundleLoader

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

Log4JBundleLoaderIT
===================

.. java:package:: org.motechproject.osgi.web.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class Log4JBundleLoaderIT

Fields
------
loader
^^^^^^

.. java:field:: @Autowired  Log4JBundleLoader loader
   :outertype: Log4JBundleLoaderIT

Methods
-------
loadBundleTest
^^^^^^^^^^^^^^

.. java:method:: @Test public void loadBundleTest() throws Exception
   :outertype: Log4JBundleLoaderIT

