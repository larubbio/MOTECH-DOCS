.. java:import:: org.motechproject.mds.dto AvailableTypeDto

.. java:import:: org.springframework.context MessageSource

.. java:import:: java.io Serializable

.. java:import:: java.util Comparator

AvailableTypeDisplayNameComparator
==================================

.. java:package:: org.motechproject.mds.web.comparator
   :noindex:

.. java:type:: public class AvailableTypeDisplayNameComparator implements Comparator<AvailableTypeDto>, Serializable

   The \ ``AvailableTypeDisplayNameComparator``\  compares two objects of \ :java:ref:`org.motechproject.mds.dto.AvailableTypeDto`\  type by value of their display name key (it ignores case differences in values).

Constructors
------------
AvailableTypeDisplayNameComparator
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AvailableTypeDisplayNameComparator(MessageSource messageSource)
   :outertype: AvailableTypeDisplayNameComparator

Methods
-------
compare
^^^^^^^

.. java:method:: @Override public int compare(AvailableTypeDto one, AvailableTypeDto two)
   :outertype: AvailableTypeDisplayNameComparator

   {@inheritDoc}

