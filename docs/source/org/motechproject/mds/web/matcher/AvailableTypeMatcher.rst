.. java:import:: org.motechproject.mds.dto AvailableTypeDto

.. java:import:: org.springframework.context MessageSource

AvailableTypeMatcher
====================

.. java:package:: org.motechproject.mds.web.matcher
   :noindex:

.. java:type:: public class AvailableTypeMatcher extends MdsMatcher<AvailableTypeDto>

   The \ ``AvailableTypeMatcher``\  checks if the field type display name matches the given term.

Constructors
------------
AvailableTypeMatcher
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public AvailableTypeMatcher(String term, MessageSource messageSource)
   :outertype: AvailableTypeMatcher

Methods
-------
match
^^^^^

.. java:method:: @Override protected boolean match(AvailableTypeDto obj)
   :outertype: AvailableTypeMatcher

   {@inheritDoc}

