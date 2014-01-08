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

TaskAnnotationBeanPostProcessorTest
===================================

.. java:package:: org.motechproject.tasks.annotations
   :noindex:

.. java:type:: @RunWith @PrepareForTest public class TaskAnnotationBeanPostProcessorTest

Methods
-------
setUp
^^^^^

.. java:method:: @Before public void setUp() throws Exception
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldAddActionWithParams
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddActionWithParams() throws Exception
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldAddActionWithoutParams
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldAddActionWithoutParams() throws Exception
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldNotProcessWhenContextNotContainsBean
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotProcessWhenContextNotContainsBean()
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldNotRegisterChannelWhenClassNotContainsTaskChannelAnnotation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterChannelWhenClassNotContainsTaskChannelAnnotation()
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldNotRegisterChannelWhenMethodNotContainsTaskActionAnnotation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterChannelWhenMethodNotContainsTaskActionAnnotation() throws Exception
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldNotRegisterSameActionTwice
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotRegisterSameActionTwice()
   :outertype: TaskAnnotationBeanPostProcessorTest

shouldProcessForAllBeansInContext
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldProcessForAllBeansInContext()
   :outertype: TaskAnnotationBeanPostProcessorTest

