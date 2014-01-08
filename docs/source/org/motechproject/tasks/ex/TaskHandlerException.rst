.. java:import:: org.motechproject.tasks.events.constants TaskFailureCause

.. java:import:: java.util Arrays

TaskHandlerException
====================

.. java:package:: org.motechproject.tasks.ex
   :noindex:

.. java:type:: public class TaskHandlerException extends Exception

Constructors
------------
TaskHandlerException
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskHandlerException(TaskFailureCause failureCause, String messageKey)
   :outertype: TaskHandlerException

TaskHandlerException
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskHandlerException(TaskFailureCause failureCause, String messageKey, String... args)
   :outertype: TaskHandlerException

TaskHandlerException
^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskHandlerException(TaskFailureCause failureCause, String messageKey, Throwable cause, String... args)
   :outertype: TaskHandlerException

Methods
-------
getArgs
^^^^^^^

.. java:method:: public String getArgs()
   :outertype: TaskHandlerException

getFailureCause
^^^^^^^^^^^^^^^

.. java:method:: public TaskFailureCause getFailureCause()
   :outertype: TaskHandlerException

getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage()
   :outertype: TaskHandlerException

