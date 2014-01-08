.. java:import:: org.sonatype.aether.impl ArtifactDescriptorReader

.. java:import:: org.sonatype.aether.impl MetadataGeneratorFactory

.. java:import:: org.sonatype.aether.impl VersionRangeResolver

.. java:import:: org.sonatype.aether.impl VersionResolver

DefaultServiceLocator
=====================

.. java:package:: org.motechproject.admin.service.impl
   :noindex:

.. java:type:: public class DefaultServiceLocator extends org.sonatype.aether.impl.internal.DefaultServiceLocator

   A simple service locator that is already setup with all components from this library. To acquire a complete repository system, clients need to add some repository connectors for remote transfers. \ *Note:*\  This component is meant to assists those clients that employ the repository systems outside of an IoC container, Maven plugins should instead always use regular dependency injection to acquire the repository system.

   :author: Benjamin Bentmann

Constructors
------------
DefaultServiceLocator
^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public DefaultServiceLocator()
   :outertype: DefaultServiceLocator

   Creates a new service locator that already knows about all service implementations included this library.

