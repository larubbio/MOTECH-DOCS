.. java:import:: org.joda.time DateTime

.. java:import:: org.motechproject.email.domain EmailRecord

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener.annotations MotechListener

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

PurgeEmailEventHandlerImpl
==========================

.. java:package:: org.motechproject.email.service.impl
   :noindex:

.. java:type:: @Service public class PurgeEmailEventHandlerImpl

   The \ ``PurgeEmailEventHandlerImpl``\  class is responsible for handling events, connected with purging {@Link EmailRecord}s

Fields
------
PURGE_EMAIL_SUBJECT
^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PURGE_EMAIL_SUBJECT
   :outertype: PurgeEmailEventHandlerImpl

Methods
-------
handle
^^^^^^

.. java:method:: @MotechListener public void handle(MotechEvent event)
   :outertype: PurgeEmailEventHandlerImpl

