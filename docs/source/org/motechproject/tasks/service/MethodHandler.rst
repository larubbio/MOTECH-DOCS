.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Map

.. java:import:: java.util SortedSet

MethodHandler
=============

.. java:package:: org.motechproject.tasks.service
   :noindex:

.. java:type::  class MethodHandler

   Utility class used by \ :java:ref:`TaskTriggerHandler`\  to construct a list of parameter types of the method in the correct order.

Constructors
------------
MethodHandler
^^^^^^^^^^^^^

.. java:constructor:: public MethodHandler(ActionEvent action, Map<String, Object> parameters)
   :outertype: MethodHandler

Methods
-------
getClasses
^^^^^^^^^^

.. java:method:: public Class getClasses()
   :outertype: MethodHandler

getObjects
^^^^^^^^^^

.. java:method:: public Object getObjects()
   :outertype: MethodHandler

isParametrized
^^^^^^^^^^^^^^

.. java:method:: public boolean isParametrized()
   :outertype: MethodHandler

