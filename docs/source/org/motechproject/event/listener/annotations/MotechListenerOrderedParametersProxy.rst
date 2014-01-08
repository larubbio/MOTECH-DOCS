.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Map

MotechListenerOrderedParametersProxy
====================================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: public class MotechListenerOrderedParametersProxy extends MotechListenerAbstractProxy

   Dispatches ordered parameters MotechEvent {"0":Obj0, "1":Obj1, .... "n":ObjN} to appropriate method signature at runtime NOTE: It might be better append the method signature to the end of the subjects

   :author: yyonkov

Constructors
------------
MotechListenerOrderedParametersProxy
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechListenerOrderedParametersProxy(String name, Object bean, Method method)
   :outertype: MotechListenerOrderedParametersProxy

Methods
-------
callHandler
^^^^^^^^^^^

.. java:method:: @Override public void callHandler(MotechEvent event)
   :outertype: MotechListenerOrderedParametersProxy

