.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.eventlogging.converter EventToLogConverter

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.util Map

DefaultFileToLogConverter
=========================

.. java:package:: org.motechproject.eventlogging.converter.impl
   :noindex:

.. java:type:: @Component public class DefaultFileToLogConverter implements EventToLogConverter<String>

Methods
-------
convertToLog
^^^^^^^^^^^^

.. java:method:: @Override public String convertToLog(MotechEvent event)
   :outertype: DefaultFileToLogConverter

