.. java:import:: org.springframework.beans BeansException

.. java:import:: org.springframework.beans.factory BeanFactory

.. java:import:: org.springframework.beans.factory NoSuchBeanDefinitionException

.. java:import:: org.springframework.beans.factory.config AutowireCapableBeanFactory

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.context ApplicationEvent

.. java:import:: org.springframework.context MessageSourceResolvable

.. java:import:: org.springframework.context NoSuchMessageException

.. java:import:: org.springframework.core.env ConfigurableEnvironment

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.web.context ConfigurableWebApplicationContext

.. java:import:: org.springframework.web.context WebApplicationContext

.. java:import:: javax.servlet ServletContext

.. java:import:: java.io IOException

.. java:import:: java.lang.annotation Annotation

.. java:import:: java.util Locale

.. java:import:: java.util Map

OsgiWebApplicationContext
=========================

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class OsgiWebApplicationContext implements WebApplicationContext

Constructors
------------
OsgiWebApplicationContext
^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public OsgiWebApplicationContext(ApplicationContext applicationContext, ConfigurableWebApplicationContext configurableWebApplicationContext)
   :outertype: OsgiWebApplicationContext

Methods
-------
containsBean
^^^^^^^^^^^^

.. java:method:: @Override public boolean containsBean(String name)
   :outertype: OsgiWebApplicationContext

containsBeanDefinition
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean containsBeanDefinition(String beanName)
   :outertype: OsgiWebApplicationContext

containsLocalBean
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public boolean containsLocalBean(String name)
   :outertype: OsgiWebApplicationContext

findAnnotationOnBean
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public <A extends Annotation> A findAnnotationOnBean(String beanName, Class<A> annotationType)
   :outertype: OsgiWebApplicationContext

getAliases
^^^^^^^^^^

.. java:method:: @Override public String getAliases(String name)
   :outertype: OsgiWebApplicationContext

getAutowireCapableBeanFactory
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public AutowireCapableBeanFactory getAutowireCapableBeanFactory() throws IllegalStateException
   :outertype: OsgiWebApplicationContext

getBean
^^^^^^^

.. java:method:: @Override public Object getBean(String name) throws BeansException
   :outertype: OsgiWebApplicationContext

getBean
^^^^^^^

.. java:method:: @Override public <T> T getBean(String name, Class<T> requiredType) throws BeansException
   :outertype: OsgiWebApplicationContext

getBean
^^^^^^^

.. java:method:: @Override public <T> T getBean(Class<T> requiredType) throws BeansException
   :outertype: OsgiWebApplicationContext

getBean
^^^^^^^

.. java:method:: @Override public Object getBean(String name, Object... args) throws BeansException
   :outertype: OsgiWebApplicationContext

getBeanDefinitionCount
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public int getBeanDefinitionCount()
   :outertype: OsgiWebApplicationContext

getBeanDefinitionNames
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public String getBeanDefinitionNames()
   :outertype: OsgiWebApplicationContext

getBeanNamesForType
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public String getBeanNamesForType(Class<?> type)
   :outertype: OsgiWebApplicationContext

getBeanNamesForType
^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public String getBeanNamesForType(Class<?> type, boolean includeNonSingletons, boolean allowEagerInit)
   :outertype: OsgiWebApplicationContext

getBeansOfType
^^^^^^^^^^^^^^

.. java:method:: @Override public <T> Map<String, T> getBeansOfType(Class<T> type) throws BeansException
   :outertype: OsgiWebApplicationContext

getBeansOfType
^^^^^^^^^^^^^^

.. java:method:: @Override public <T> Map<String, T> getBeansOfType(Class<T> type, boolean includeNonSingletons, boolean allowEagerInit) throws BeansException
   :outertype: OsgiWebApplicationContext

getBeansWithAnnotation
^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Map<String, Object> getBeansWithAnnotation(Class<? extends Annotation> annotationType) throws BeansException
   :outertype: OsgiWebApplicationContext

getClassLoader
^^^^^^^^^^^^^^

.. java:method:: @Override public ClassLoader getClassLoader()
   :outertype: OsgiWebApplicationContext

getDisplayName
^^^^^^^^^^^^^^

.. java:method:: @Override public String getDisplayName()
   :outertype: OsgiWebApplicationContext

getEnvironment
^^^^^^^^^^^^^^

.. java:method:: @Override public ConfigurableEnvironment getEnvironment()
   :outertype: OsgiWebApplicationContext

getId
^^^^^

.. java:method:: @Override public String getId()
   :outertype: OsgiWebApplicationContext

getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage(String code, Object args, String defaultMessage, Locale locale)
   :outertype: OsgiWebApplicationContext

getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage(String code, Object args, Locale locale) throws NoSuchMessageException
   :outertype: OsgiWebApplicationContext

getMessage
^^^^^^^^^^

.. java:method:: @Override public String getMessage(MessageSourceResolvable resolvable, Locale locale) throws NoSuchMessageException
   :outertype: OsgiWebApplicationContext

getParent
^^^^^^^^^

.. java:method:: @Override public ApplicationContext getParent()
   :outertype: OsgiWebApplicationContext

getParentBeanFactory
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public BeanFactory getParentBeanFactory()
   :outertype: OsgiWebApplicationContext

getResource
^^^^^^^^^^^

.. java:method:: @Override public Resource getResource(String location)
   :outertype: OsgiWebApplicationContext

getResources
^^^^^^^^^^^^

.. java:method:: @Override public Resource getResources(String locationPattern) throws IOException
   :outertype: OsgiWebApplicationContext

getServletContext
^^^^^^^^^^^^^^^^^

.. java:method:: @Override public ServletContext getServletContext()
   :outertype: OsgiWebApplicationContext

getStartupDate
^^^^^^^^^^^^^^

.. java:method:: @Override public long getStartupDate()
   :outertype: OsgiWebApplicationContext

getType
^^^^^^^

.. java:method:: @Override public Class<?> getType(String name) throws NoSuchBeanDefinitionException
   :outertype: OsgiWebApplicationContext

isPrototype
^^^^^^^^^^^

.. java:method:: @Override public boolean isPrototype(String name) throws NoSuchBeanDefinitionException
   :outertype: OsgiWebApplicationContext

isSingleton
^^^^^^^^^^^

.. java:method:: @Override public boolean isSingleton(String name) throws NoSuchBeanDefinitionException
   :outertype: OsgiWebApplicationContext

isTypeMatch
^^^^^^^^^^^

.. java:method:: @Override public boolean isTypeMatch(String name, Class<?> targetType) throws NoSuchBeanDefinitionException
   :outertype: OsgiWebApplicationContext

publishEvent
^^^^^^^^^^^^

.. java:method:: @Override public void publishEvent(ApplicationEvent event)
   :outertype: OsgiWebApplicationContext

