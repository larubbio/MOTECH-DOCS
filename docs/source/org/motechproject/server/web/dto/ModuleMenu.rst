.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util List

ModuleMenu
==========

.. java:package:: org.motechproject.server.web.dto
   :noindex:

.. java:type:: public class ModuleMenu implements Serializable

   Class representing the left hand side menu. Contains a list of sections to display.

Methods
-------
addMenuSection
^^^^^^^^^^^^^^

.. java:method:: public void addMenuSection(ModuleMenuSection section)
   :outertype: ModuleMenu

getSections
^^^^^^^^^^^

.. java:method:: public List<ModuleMenuSection> getSections()
   :outertype: ModuleMenu

setSections
^^^^^^^^^^^

.. java:method:: public void setSections(List<ModuleMenuSection> sections)
   :outertype: ModuleMenu

