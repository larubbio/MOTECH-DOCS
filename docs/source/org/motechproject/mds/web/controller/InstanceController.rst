.. java:import:: org.motechproject.mds.dto EntityDto

.. java:import:: org.motechproject.mds.dto FieldDto

.. java:import:: org.motechproject.mds.dto FieldInstanceDto

.. java:import:: org.motechproject.mds.ex EntityNotFoundException

.. java:import:: org.motechproject.mds.web.comparator HistoryRecordComparator

.. java:import:: org.motechproject.mds.web.domain GridSettings

.. java:import:: org.motechproject.mds.web.domain HistoryRecord

.. java:import:: org.motechproject.mds.web.domain Records

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util Collections

.. java:import:: java.util List

InstanceController
==================

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: @Controller public class InstanceController extends MdsController

   The \ ``FieldController``\  is the Spring Framework Controller used by view layer for executing certain actions on entity fields.

Methods
-------
getHistory
^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Records<HistoryRecord> getHistory(String instanceId, GridSettings settings)
   :outertype: InstanceController

getInstanceFields
^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<FieldInstanceDto> getInstanceFields(String instanceId)
   :outertype: InstanceController

