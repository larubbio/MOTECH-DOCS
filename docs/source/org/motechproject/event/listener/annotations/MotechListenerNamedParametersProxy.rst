.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.springframework.util Assert

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.annotation Annotation

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MotechListenerNamedParametersProxy
==================================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: public class MotechListenerNamedParametersProxy extends MotechListenerAbstractProxy

   :author: yyonkov

Constructors
------------
MotechListenerNamedParametersProxy
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechListenerNamedParametersProxy(String name, Object bean, Method method)
   :outertype: MotechListenerNamedParametersProxy

   :param name:
   :param bean:
   :param method:

Methods
-------
callHandler
^^^^^^^^^^^

.. java:method:: @Override public void callHandler(MotechEvent event)
   :outertype: MotechListenerNamedParametersProxy

