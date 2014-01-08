.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.motechproject.event.listener.annotations MotechListenerEventProxy

.. java:import:: org.motechproject.tasks.domain Task

HandlerPredicates
=================

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type:: final class HandlerPredicates

   Utility class defining filters over some collections.

Methods
-------
activeTasks
^^^^^^^^^^^

.. java:method:: public static Predicate activeTasks()
   :outertype: HandlerPredicates

withServiceName
^^^^^^^^^^^^^^^

.. java:method:: public static Predicate withServiceName(String serviceName)
   :outertype: HandlerPredicates

