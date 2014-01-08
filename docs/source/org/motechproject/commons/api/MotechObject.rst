.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

MotechObject
============

.. java:package:: org.motechproject.commons.api
   :noindex:

.. java:type:: public class MotechObject

   LayerSupertype for entire motech project. Used optionally through the motech project.

Methods
-------
assertArgumentNotEmpty
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void assertArgumentNotEmpty(String objectName, String argument)
   :outertype: MotechObject

assertArgumentNotNull
^^^^^^^^^^^^^^^^^^^^^

.. java:method:: protected void assertArgumentNotNull(String objectName, Object object)
   :outertype: MotechObject

logError
^^^^^^^^

.. java:method:: protected void logError(String templateMessage, Object... params)
   :outertype: MotechObject

logError
^^^^^^^^

.. java:method:: protected void logError(String message)
   :outertype: MotechObject

logError
^^^^^^^^

.. java:method:: protected void logError(String message, Exception e)
   :outertype: MotechObject

logInfo
^^^^^^^

.. java:method:: protected void logInfo(String templateMessage, Object... params)
   :outertype: MotechObject

logger
^^^^^^

.. java:method:: protected Logger logger()
   :outertype: MotechObject

