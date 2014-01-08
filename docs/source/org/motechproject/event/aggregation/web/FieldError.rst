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

FieldError
==========

.. java:package:: org.motechproject.event.aggregation.web
   :noindex:

.. java:type::  class FieldError extends RequestError

Constructors
------------
FieldError
^^^^^^^^^^

.. java:constructor::  FieldError(String field, String errorMessage)
   :outertype: FieldError

Methods
-------
getField
^^^^^^^^

.. java:method:: public String getField()
   :outertype: FieldError

