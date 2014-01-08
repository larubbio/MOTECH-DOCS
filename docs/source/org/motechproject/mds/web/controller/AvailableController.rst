.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.motechproject.mds.dto AvailableTypeDto

.. java:import:: org.motechproject.mds.web SelectData

.. java:import:: org.motechproject.mds.web SelectResult

.. java:import:: org.motechproject.mds.web.comparator AvailableTypeDisplayNameComparator

.. java:import:: org.motechproject.mds.web.matcher AvailableTypeMatcher

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context MessageSource

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util Collections

.. java:import:: java.util List

AvailableController
===================

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: @Controller public class AvailableController extends MdsController

   The \ ``AvailableController``\  is the Spring Framework Controller used by view layer for get list of available objects (like a field types).

Constructors
------------
AvailableController
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AvailableController(MessageSource messageSource)
   :outertype: AvailableController

Methods
-------
getTypes
^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public SelectResult<AvailableTypeDto> getTypes(SelectData data)
   :outertype: AvailableController

