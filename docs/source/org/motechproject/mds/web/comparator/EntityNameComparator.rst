.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: java.io Serializable

.. java:import:: java.util Comparator

EntityNameComparator
====================

.. java:package:: org.motechproject.mds.web.comparator
   :noindex:

.. java:type:: public class EntityNameComparator implements Comparator<EntityDto>, Serializable

   The \ ``EntityNameComparator``\  compares two objects of \ :java:ref:`org.motechproject.mds.dto.EntityDto`\  type by their name (it ignores case differences in names).

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(EntityDto one, EntityDto two)
   :outertype: EntityNameComparator

   {@inheritDoc}

