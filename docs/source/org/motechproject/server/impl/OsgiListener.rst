.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.web.context.support WebApplicationContextUtils

.. java:import:: javax.servlet ServletContext

.. java:import:: javax.servlet ServletContextEvent

.. java:import:: javax.servlet ServletContextListener

OsgiListener
============

.. java:package:: org.motechproject.server.impl
   :noindex:

.. java:type:: public class OsgiListener implements ServletContextListener

Methods
-------
contextDestroyed
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void contextDestroyed(ServletContextEvent servletContextEvent)
   :outertype: OsgiListener

contextInitialized
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void contextInitialized(ServletContextEvent servletContextEvent)
   :outertype: OsgiListener

getOsgiService
^^^^^^^^^^^^^^

.. java:method:: public static OsgiFrameworkService getOsgiService()
   :outertype: OsgiListener

