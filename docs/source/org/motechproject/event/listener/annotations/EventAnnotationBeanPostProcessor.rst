.. java:import:: org.motechproject.event.listener EventListenerRegistryService

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.aop.support AopUtils

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.config DestructionAwareBeanPostProcessor

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.reflect Method

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Map

EventAnnotationBeanPostProcessor
================================

.. java:package:: org.motechproject.event.listener.annotations
   :noindex:

.. java:type:: public class EventAnnotationBeanPostProcessor implements DestructionAwareBeanPostProcessor

   Responsible for registering handlers based on annotations

   Create a bean only when module has MotechEvent annotations.

   :author: yyonkov

Constructors
------------
EventAnnotationBeanPostProcessor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventAnnotationBeanPostProcessor()
   :outertype: EventAnnotationBeanPostProcessor

EventAnnotationBeanPostProcessor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EventAnnotationBeanPostProcessor(EventListenerRegistryService eventListenerRegistryService)
   :outertype: EventAnnotationBeanPostProcessor

Methods
-------
clearListenerForBean
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void clearListenerForBean(String beanName)
   :outertype: EventAnnotationBeanPostProcessor

clearListeners
^^^^^^^^^^^^^^

.. java:method:: public void clearListeners(ApplicationContext applicationContext)
   :outertype: EventAnnotationBeanPostProcessor

postProcessAfterInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessAfterInitialization(Object bean, String beanName)
   :outertype: EventAnnotationBeanPostProcessor

postProcessBeforeDestruction
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void postProcessBeforeDestruction(Object bean, String beanName)
   :outertype: EventAnnotationBeanPostProcessor

postProcessBeforeInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessBeforeInitialization(Object bean, String beanName)
   :outertype: EventAnnotationBeanPostProcessor

processAnnotations
^^^^^^^^^^^^^^^^^^

.. java:method:: public void processAnnotations(ApplicationContext applicationContext)
   :outertype: EventAnnotationBeanPostProcessor

processAnnotations
^^^^^^^^^^^^^^^^^^

.. java:method:: public void processAnnotations(Object bean, String beanName)
   :outertype: EventAnnotationBeanPostProcessor

registerHandlers
^^^^^^^^^^^^^^^^

.. java:method:: public static void registerHandlers(Map<String, Object> beans)
   :outertype: EventAnnotationBeanPostProcessor

   Registers event handlers (hack because we are running spring embedded in an OSGi module)

setEventListenerRegistry
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Autowired public void setEventListenerRegistry(EventListenerRegistryService eventListenerRegistry)
   :outertype: EventAnnotationBeanPostProcessor

