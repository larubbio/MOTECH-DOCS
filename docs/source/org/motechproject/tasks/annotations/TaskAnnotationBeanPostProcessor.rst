.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain TaskActionInformation

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.beans.factory.config BeanPostProcessor

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.util ReflectionUtils

.. java:import:: java.lang.annotation Annotation

.. java:import:: java.lang.reflect Method

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

TaskAnnotationBeanPostProcessor
===============================

.. java:package:: org.motechproject.tasks.annotations
   :noindex:

.. java:type:: public class TaskAnnotationBeanPostProcessor implements BeanPostProcessor

   Factory class which is looking for classes with \ :java:ref:`TaskChannel`\  annotation to add them to the channel definition as channel action.

Constructors
------------
TaskAnnotationBeanPostProcessor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public TaskAnnotationBeanPostProcessor(BundleContext bundleContext, ChannelService channelService)
   :outertype: TaskAnnotationBeanPostProcessor

Methods
-------
postProcessAfterInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessAfterInitialization(Object bean, String beanName)
   :outertype: TaskAnnotationBeanPostProcessor

postProcessBeforeInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessBeforeInitialization(Object bean, String beanName)
   :outertype: TaskAnnotationBeanPostProcessor

processAnnotations
^^^^^^^^^^^^^^^^^^

.. java:method:: public void processAnnotations(ApplicationContext applicationContext)
   :outertype: TaskAnnotationBeanPostProcessor

