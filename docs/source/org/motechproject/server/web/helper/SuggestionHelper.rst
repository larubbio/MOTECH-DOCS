.. java:import:: org.apache.activemq ActiveMQConnectionFactory

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.jms Connection

.. java:import:: javax.jms ConnectionFactory

.. java:import:: javax.jms JMSException

SuggestionHelper
================

.. java:package:: org.motechproject.server.web.helper
   :noindex:

.. java:type:: @Component public class SuggestionHelper

   Helper class for creating UI suggestions for the user. Checks default locations for available services.

Fields
------
DEFAULT_ACTIVEMQ_URL
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String DEFAULT_ACTIVEMQ_URL
   :outertype: SuggestionHelper

Methods
-------
suggestActivemqUrl
^^^^^^^^^^^^^^^^^^

.. java:method:: public String suggestActivemqUrl()
   :outertype: SuggestionHelper

   Suggests the ActiveMQ url.

   :return: The suggested url, or an empty string if the instance is not found.

