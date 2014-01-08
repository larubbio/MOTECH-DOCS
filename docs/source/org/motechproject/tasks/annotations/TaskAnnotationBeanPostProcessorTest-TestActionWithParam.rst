.. java:import:: org.apache.commons.collections Predicate

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.mockito ArgumentCaptor

.. java:import:: org.mockito Mock

.. java:import:: org.motechproject.tasks.domain ActionEvent

.. java:import:: org.motechproject.tasks.domain ActionParameter

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: org.motechproject.tasks.service ChannelService

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.osgi.framework ServiceReference

.. java:import:: org.powermock.api.mockito PowerMockito

.. java:import:: org.powermock.core.classloader.annotations PrepareForTest

.. java:import:: org.powermock.modules.junit4 PowerMockRunner

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.core.annotation AnnotationUtils

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation PathVariable

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: java.io Serializable

.. java:import:: java.util SortedSet

.. java:import:: java.util TreeSet

TaskAnnotationBeanPostProcessorTest.TestActionWithParam
=======================================================

.. java:package:: org.motechproject.tasks.annotations
   :noindex:

.. java:type:: @Controller @TaskChannel  class TestActionWithParam implements TestAction
   :outertype: TaskAnnotationBeanPostProcessorTest

Methods
-------
action
^^^^^^

.. java:method:: @RequestMapping @TaskAction @Override public void action(String externalId, Integer motechId, String message)
   :outertype: TaskAnnotationBeanPostProcessorTest.TestActionWithParam

