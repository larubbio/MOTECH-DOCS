.. java:import:: org.motechproject.event.aggregation.model Aggregation

.. java:import:: org.motechproject.event.aggregation.repository AllAggregatedEvents

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind ServletRequestBindingException

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: java.util List

AggregationController
=====================

.. java:package:: org.motechproject.event.aggregation.web
   :noindex:

.. java:type:: @Controller @RequestMapping public class AggregationController

Methods
-------
getAggregations
^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<? extends Aggregation> getAggregations(String ruleName, String eventStatus) throws ServletRequestBindingException
   :outertype: AggregationController

