.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.tasks.ex TriggerNotFoundException

TriggerHandler
==============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: public interface TriggerHandler

   Standard interface for tasks which executes tasks.

Methods
-------
handle
^^^^^^

.. java:method::  void handle(MotechEvent event) throws TriggerNotFoundException
   :outertype: TriggerHandler

registerHandlerFor
^^^^^^^^^^^^^^^^^^

.. java:method::  void registerHandlerFor(String subject)
   :outertype: TriggerHandler

