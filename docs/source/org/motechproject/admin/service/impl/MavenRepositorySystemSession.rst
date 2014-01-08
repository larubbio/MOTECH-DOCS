.. java:import:: org.sonatype.aether.collection DependencyGraphTransformer

.. java:import:: org.sonatype.aether.collection DependencyManager

.. java:import:: org.sonatype.aether.collection DependencySelector

.. java:import:: org.sonatype.aether.collection DependencyTraverser

.. java:import:: org.sonatype.aether.util DefaultRepositorySystemSession

.. java:import:: org.sonatype.aether.util.artifact DefaultArtifactType

.. java:import:: org.sonatype.aether.util.artifact DefaultArtifactTypeRegistry

.. java:import:: org.sonatype.aether.util.graph.manager ClassicDependencyManager

.. java:import:: org.sonatype.aether.util.graph.selector AndDependencySelector

.. java:import:: org.sonatype.aether.util.graph.selector ExclusionDependencySelector

.. java:import:: org.sonatype.aether.util.graph.selector OptionalDependencySelector

.. java:import:: org.sonatype.aether.util.graph.selector ScopeDependencySelector

.. java:import:: org.sonatype.aether.util.graph.transformer ChainedDependencyGraphTransformer

.. java:import:: org.sonatype.aether.util.graph.transformer ConflictMarker

.. java:import:: org.sonatype.aether.util.graph.transformer JavaDependencyContextRefiner

.. java:import:: org.sonatype.aether.util.graph.transformer JavaEffectiveScopeCalculator

.. java:import:: org.sonatype.aether.util.graph.transformer NearestVersionConflictResolver

.. java:import:: org.sonatype.aether.util.graph.traverser FatArtifactTraverser

.. java:import:: org.sonatype.aether.util.repository DefaultAuthenticationSelector

.. java:import:: org.sonatype.aether.util.repository DefaultMirrorSelector

.. java:import:: org.sonatype.aether.util.repository DefaultProxySelector

MavenRepositorySystemSession
============================

.. java:package:: org.motechproject.admin.service.impl
   :noindex:

.. java:type:: public class MavenRepositorySystemSession extends DefaultRepositorySystemSession

   A simplistic repository system session that mimics Maven's behavior to help third-party developers that want to embed Maven's dependency resolution into their own applications. \ **Warning:**\  This class is not intended for usage by Maven plugins, those should always acquire the current repository system session via parameter injection.

   :author: Benjamin Bentmann

Constructors
------------
MavenRepositorySystemSession
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MavenRepositorySystemSession()
   :outertype: MavenRepositorySystemSession

   Creates a new Maven-like repository system session by initializing the session with values typical for Maven-based resolution.

