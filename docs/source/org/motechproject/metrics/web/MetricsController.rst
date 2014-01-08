.. java:import:: org.motechproject.metrics StatsdAgentBackend

.. java:import:: org.motechproject.metrics.domain ConfigProperty

.. java:import:: org.motechproject.metrics.domain PropertyType

.. java:import:: org.motechproject.metrics.exception ValidationException

.. java:import:: org.motechproject.metrics.util MetricsAgentBackendManager

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.util HashMap

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util Set

MetricsController
=================

.. java:package:: org.motechproject.metrics.web
   :noindex:

.. java:type:: @Controller public class MetricsController

Methods
-------
getAllAvailableImplementations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Set<String> getAllAvailableImplementations()
   :outertype: MetricsController

getBackendSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Map<String, ConfigProperty> getBackendSettings(String implName)
   :outertype: MetricsController

getGraphiteUrl
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String getGraphiteUrl()
   :outertype: MetricsController

getUsedImplementations
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public List<String> getUsedImplementations()
   :outertype: MetricsController

handleException
^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleException(ValidationException e)
   :outertype: MetricsController

setBackendSettings
^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void setBackendSettings(String implName, Map<String, Map<String, String>> config)
   :outertype: MetricsController

setUsedImplementations
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @ResponseStatus @RequestMapping public void setUsedImplementations(List<String> selected)
   :outertype: MetricsController

