.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.event MotechEvent

.. java:import:: org.motechproject.event.listener EventListener

.. java:import:: org.slf4j LoggerFactory

.. java:import:: java.lang.reflect Method

MotechListenerAbstractProxy
===========================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: public abstract class MotechListenerAbstractProxy implements EventListener

   Event Listener Proxy base abstract class

   :author: yyonkov

Constructors
------------
MotechListenerAbstractProxy
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechListenerAbstractProxy(String name, Object bean, Method method)
   :outertype: MotechListenerAbstractProxy

   :param name:
   :param bean:
   :param method:

Methods
-------
callHandler
^^^^^^^^^^^

.. java:method:: public abstract void callHandler(MotechEvent event)
   :outertype: MotechListenerAbstractProxy

   Needs to be implemented by concrete Proxies

   :param event:

getBean
^^^^^^^

.. java:method:: public Object getBean()
   :outertype: MotechListenerAbstractProxy

getIdentifier
^^^^^^^^^^^^^

.. java:method:: @Override public String getIdentifier()
   :outertype: MotechListenerAbstractProxy

getMethod
^^^^^^^^^

.. java:method:: public Method getMethod()
   :outertype: MotechListenerAbstractProxy

handle
^^^^^^

.. java:method:: @Override public void handle(MotechEvent event)
   :outertype: MotechListenerAbstractProxy

