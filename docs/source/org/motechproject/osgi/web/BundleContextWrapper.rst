.. java:import:: org.eclipse.gemini.blueprint.context BundleContextAware

.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.osgi.framework Bundle

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework InvalidSyntaxException

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.context ApplicationContext

BundleContextWrapper
====================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class BundleContextWrapper implements BundleContextAware

Fields
------
CONTEXT_SERVICE_NAME
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String CONTEXT_SERVICE_NAME
   :outertype: BundleContextWrapper

Constructors
------------
BundleContextWrapper
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BundleContextWrapper()
   :outertype: BundleContextWrapper

BundleContextWrapper
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BundleContextWrapper(BundleContext context)
   :outertype: BundleContextWrapper

Methods
-------
getBundleApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public ApplicationContext getBundleApplicationContext()
   :outertype: BundleContextWrapper

getBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: public BundleContext getBundleContext()
   :outertype: BundleContextWrapper

getCurrentBundleSymbolicName
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: public String getCurrentBundleSymbolicName()
   :outertype: BundleContextWrapper

getService
^^^^^^^^^^

.. java:method:: public <T> T getService(Class<T> clazz)
   :outertype: BundleContextWrapper

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setBundleContext(BundleContext bundleContext)
   :outertype: BundleContextWrapper

