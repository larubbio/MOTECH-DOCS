.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: java.util List

EntityMatcher
=============

.. java:package:: org.motechproject.mds.web.matcher
   :noindex:

.. java:type:: public class EntityMatcher extends MdsMatcher<EntityDto>

   The \ ``EntityMatcher``\  checks if the entity name, module or namespace matches the given term.

Constructors
------------
EntityMatcher
^^^^^^^^^^^^^

.. java:constructor:: public EntityMatcher(String term)
   :outertype: EntityMatcher

Methods
-------
match
^^^^^

.. java:method:: @Override protected boolean match(EntityDto obj)
   :outertype: EntityMatcher

   {@inheritDoc}

