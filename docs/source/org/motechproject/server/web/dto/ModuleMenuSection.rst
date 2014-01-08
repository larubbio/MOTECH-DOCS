.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ModuleMenuSection
=================

.. java:package:: org.motechproject.server.web.dto
   :noindex:

.. java:type:: public class ModuleMenuSection implements Serializable

   A class representing a section in the left hand nav menu. Apart from its name, it also contains a list links to be displayed in this section. The \ :java:ref:`isNeedsAttention()`\  flag specifies whether this section should be given a warning icon on the UI.

Constructors
------------
ModuleMenuSection
^^^^^^^^^^^^^^^^^

.. java:constructor:: public ModuleMenuSection(String name, boolean needsAttention)
   :outertype: ModuleMenuSection

Methods
-------
addLink
^^^^^^^

.. java:method:: public void addLink(ModuleMenuLink link)
   :outertype: ModuleMenuSection

getLinks
^^^^^^^^

.. java:method:: public List<ModuleMenuLink> getLinks()
   :outertype: ModuleMenuSection

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: ModuleMenuSection

hasLinkFor
^^^^^^^^^^

.. java:method:: public boolean hasLinkFor(String url)
   :outertype: ModuleMenuSection

isNeedsAttention
^^^^^^^^^^^^^^^^

.. java:method:: public boolean isNeedsAttention()
   :outertype: ModuleMenuSection

setLinks
^^^^^^^^

.. java:method:: public void setLinks(List<ModuleMenuLink> links)
   :outertype: ModuleMenuSection

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: ModuleMenuSection

setNeedsAttention
^^^^^^^^^^^^^^^^^

.. java:method:: public void setNeedsAttention(boolean needsAttention)
   :outertype: ModuleMenuSection

