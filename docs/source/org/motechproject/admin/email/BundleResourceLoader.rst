.. java:import:: org.apache.velocity.runtime.resource.loader ClasspathResourceLoader

.. java:import:: java.io InputStream

BundleResourceLoader
====================

.. java:package:: org.motechproject.admin.email
   :noindex:

.. java:type:: public class BundleResourceLoader extends ClasspathResourceLoader

   A resource loader required to properly load velocity templates from classpath in OSGi. When retrieving the stream, we need to use this bundle's \ :java:ref:`ClassLoader`\ , instead of the one coming from the Velocity bundle.

Methods
-------
getResourceStream
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public InputStream getResourceStream(String name)
   :outertype: BundleResourceLoader

