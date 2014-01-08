.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.codehaus.jackson.map ObjectMapper

.. java:import:: org.hibernate.validator ValidatorFactoryBean

.. java:import:: org.motechproject.event.aggregation.model.mapper AggregationRuleMapper

.. java:import:: org.motechproject.event.aggregation.repository AllAggregationRules

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRule

.. java:import:: org.motechproject.event.aggregation.model.rule AggregationRuleRequest

.. java:import:: org.motechproject.event.aggregation.service EventAggregationService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.http.converter HttpMessageNotReadableException

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: javax.validation ConstraintViolation

.. java:import:: javax.validation Validator

.. java:import:: java.io IOException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Set

AggregationRuleController
=========================

.. java:package:: org.motechproject.event.aggregation.web
   :noindex:

.. java:type:: @Controller @RequestMapping public class AggregationRuleController

Constructors
------------
AggregationRuleController
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public AggregationRuleController(AllAggregationRules allAggregationRules)
   :outertype: AggregationRuleController

Methods
-------
addOrReplace
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus @ResponseBody public void addOrReplace(AggregationRuleRequest aggregationRule)
   :outertype: AggregationRuleController

delete
^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void delete(String ruleName)
   :outertype: AggregationRuleController

get
^^^

.. java:method:: @RequestMapping @ResponseBody public AggregationRuleRequest get(String ruleName)
   :outertype: AggregationRuleController

getAllAggregationRules
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<? extends AggregationRule> getAllAggregationRules()
   :outertype: AggregationRuleController

handleMethodArgumentNotValidException
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleMethodArgumentNotValidException(Exception exception) throws IOException
   :outertype: AggregationRuleController

