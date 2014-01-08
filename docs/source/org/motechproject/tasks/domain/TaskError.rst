.. java:import:: java.io Serializable

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Objects

TaskError
=========

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public class TaskError implements Serializable

Constructors
------------
TaskError
^^^^^^^^^

.. java:constructor:: public TaskError()
   :outertype: TaskError

TaskError
^^^^^^^^^

.. java:constructor:: public TaskError(TaskErrorType type, String... args)
   :outertype: TaskError

TaskError
^^^^^^^^^

.. java:constructor:: public TaskError(String message, String... args)
   :outertype: TaskError

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: TaskError

getArgs
^^^^^^^

.. java:method:: public List<String> getArgs()
   :outertype: TaskError

getMessage
^^^^^^^^^^

.. java:method:: public String getMessage()
   :outertype: TaskError

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: TaskError

setArgs
^^^^^^^

.. java:method:: public void setArgs(List<String> args)
   :outertype: TaskError

setMessage
^^^^^^^^^^

.. java:method:: public void setMessage(String message)
   :outertype: TaskError

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: TaskError

