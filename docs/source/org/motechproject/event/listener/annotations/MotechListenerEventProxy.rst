.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.reflect Method

MotechListenerEventProxy
========================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: public class MotechListenerEventProxy extends MotechListenerAbstractProxy

   Responsible for dispatching to \ ``void doSomething(MotechEvent event) {}``\  type of handlers

   :author: yyonkov

Constructors
------------
MotechListenerEventProxy
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechListenerEventProxy(String name, Object bean, Method method)
   :outertype: MotechListenerEventProxy

   :param name:
   :param bean:
   :param method:

Methods
-------
callHandler
^^^^^^^^^^^

.. java:method:: @Override public void callHandler(MotechEvent event)
   :outertype: MotechListenerEventProxy

